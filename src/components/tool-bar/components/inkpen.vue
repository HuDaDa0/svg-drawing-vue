<template>
  <!-- 钢笔 -->
  <div class="inkpen pen" data-type="inkpen">
    <svg
      id="inkpen-svg"
      class="tool-button"
      aria-hidden="true"
      xmlns="http://www.w3.org/2000/svg"
    >
      <g fill="none" fill-rule="evenodd">
        <path class="inkpen-accent" d="M48 5L4 4v23.965L48 27z"></path>
        <path
          class="inkpen-shadow"
          d="M4 21.224V28l43.61-1.002v-5.774z"
          fill="#5F6368"
        ></path>
        <path
          class="inkpen-nib"
          d="M76.097 24.8c.22-.041.443-.09.667-.143.12-.028.24-.06.36-.091.09-.024.179-.046.27-.071.176-.049.354-.1.532-.155l.02-.007c2.697-.827 5.492-2.294 8.048-3.81l.04-.023h-.002c.69-.41 1.363-.821 2.011-1.225C91.657 17.024 95 16.384 95 16.384V16H56.012v4.164a.194.194 0 0 0-.012-.002v2.387l8.388 1.278c.532.054 1.063.116 1.593.184l.168.022a61.717 61.717 0 0 1 2.935.454c1.256.227 2.753.47 4.28.507.915.024 1.841-.025 2.733-.193M95 14.685s-3.344-.708-6.959-2.96c-1.466-.912-3.056-1.868-4.692-2.734-2.4-1.27-4.9-2.345-7.258-2.791-2.377-.45-4.999-.05-7.003.313a61.885 61.885 0 0 1-4.697.66L56 8.451V15h39v-.315zM51 5l-4.483-.036C46.184 8.328 46 12.201 46 16.093c0 3.893.184 7.579.517 10.944L51 27V5z"
          fill="#202124"
        ></path>
        <path
          class="inkpen-channel"
          d="M75.114 13.297a2.25 2.25 0 1 1-.001 4.5 2.25 2.25 0 0 1 .001-4.5"
          fill="#f1f3f4"
        ></path>
        <path class="inkpen-channel" d="M56 15v1h39v-1z" fill="#000000"></path>
        <path
          class="inkpen-section"
          d="M54 27.204V4.796c0-.44-.435-.796-.97-.796h-1.06c-.535 0-.97.356-.97.796v22.408c0 .44.435.796.97.796h1.06c.535 0 .97-.357.97-.796"
          fill="#bdc1c6"
        ></path>
        <path
          class="inkpen-collar"
          d="M54 15.747V27l1.688-1.394a.827.827 0 0 0 .298-.638V21.55l.014-.018v-.061l-.014-1.513v-.13c.005-.007.01-.013.014-.021v-3.134l-.014-1.74-.001.002-.012-2.368s.006-5.702-.006-5.76a.825.825 0 0 0-.279-.413L54 5v10.747zM95 14.536c.552 0 1 .453 1 1.012 0 .559-.448 1.012-1 1.012s-1-.453-1-1.012c0-.56.448-1.012 1-1.012"
          fill="#f1f3f4"
        ></path>
      </g>
    </svg>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";

@Component({})
export default class Inkpen extends Vue {}
</script>
