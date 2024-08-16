<template>
    <div class="clickable-glass" >
      <GlassContainer
        :width="width"
        :height="height"
        :block="block"
        :class="{ 'glass-hovered': isHovered }"
        @mouseenter="isHovered = true"
        @mouseleave="isHovered = false"
        @click="toggleExpand"
        >
        <div class="title">{{ title }}</div>
        <div class="content" :class="{ 'expanded': isExpanded, 'collapsed': !isExpanded }">
          <slot />
        </div>
      </GlassContainer>
    </div>
  </template>
  
  <script>
  import GlassContainer from './GlassContainer.vue';
  
  export default {
    name: 'ClickableGlass',
    components: {
      GlassContainer,
    },
    props: {
      width: {
        type: String,
        default: 'auto',
      },
      height: {
        type: String,
        default: 'auto',
      },
      block: {
        type: Boolean,
        default: false,
      },
      expandable: {
        type: Boolean,
        default: false,
      },
      title: {
        type: String,
        default: 'Click to Expand',
      },
    },
    data() {
      return {
        isHovered: false,
        isExpanded: !this.expandable, // Start expanded if not expandable
      };
    },
    methods: {
      toggleExpand() {
        if (this.expandable) {
          this.isExpanded = !this.isExpanded;
        }
      },
    },
  };
  </script>
  
  <style scoped>
  
  .frosted-glass-container {
    /* No animation styles here */
  }
  
  .glass-hovered {
    position: relative;
    overflow: hidden;
    cursor: pointer;
    transform: scale(0.95);
    transition: transform 0.3s ease;
  }
  
  .title {
    font-weight: bold;
    margin-bottom: 10px;
    z-index: 2;
    position: relative;
  }
  
  .content {
    overflow: hidden;
    opacity: 0;
  }
  
  .content.expanded {
    display: block;
    opacity: 1;
  }
  
  .content.collapsed {
    display: none;
    opacity: 0;
  }
  </style>
  