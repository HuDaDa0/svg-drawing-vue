<template>
  <path
    :d="element.path"
    :fill="element.fill"
    :stroke="element.stroke"
    :stroke-width="element.strokeWidth"
    stroke-linecap="round"
    stroke-linejoin="round"
  ></path>
</template>

<script lang="ts">
import { Component, Vue, Prop } from "vue-property-decorator";
import { SVGElement } from "@/store/options";

@Component({})
export default class CreatePath extends Vue {
  @Prop()
  element!: SVGElement;
}
</script>
