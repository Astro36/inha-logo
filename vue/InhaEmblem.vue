<template>
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 303.2 303.2" :width="size" :height="size">
    <path
      :fill="black"
      d="M208.8 102.5h-22.2v-5.6h-8.5V72.7h-33.9c-13.1 0-20.9 8.8-20.9 21.9v7.9H96.7l-11 103.8 67.1 28.5 67-28.5zm-56 129.9l-64.7-27.5 10.6-100.2h26.9c.5-6.6-1.9-16.8 4.6-24.2 3.3-3.7 8.1-5.6 14-5.6h31.7v24.2h8.5v5.6h22.4l10.6 100.2zm-6.3-145.1c-3.2 0-6.6 2.3-6.6 7.4v10h9.8V87.3zm1 15.2h-5.4v-7.8c0-3.8 2.4-5.2 4.4-5.2h1zM151.6 0a151.6 151.6 0 1 0 151.6 151.6A151.6 151.6 0 0 0 151.6 0zm0 299.1a147.5 147.5 0 1 1 147.5-147.5 147.5 147.5 0 0 1-147.5 147.5zm0-244.1a96.5 96.5 0 1 0 .2 0zm0 191a94.4 94.4 0 1 1 94.4-94.4 94.39 94.39 0 0 1-94.4 94.4zm-123-89.5a5.8 5.8 0 1 0-5.8-5.8 5.8 5.8 0 0 0 5.8 5.8zm248.8 0a5.8 5.8 0 1 0-5.8-5.8 5.8 5.8 0 0 0 5.8 5.8zM43.5 177l-.7-2.9.7-.2 2.4 9.4-.8.2-.7-2.9-20.6 5.2.7 2.9-.7.2-2.4-9.4.8-.2.7 3zm3.6 12.6l-1.1-2.7.7-.3 3 6.7-10.3 17 14.1-6.2-1.4-3.2.8-.3 3 6.7-.8.3-1.2-2.7-20.3 9.1-.4-.5 13.7-22.6-18.8 8.3 1.4 3.2-.7.4-3-6.8.7-.3 1.2 2.7zm19 33.2l-1.8-2.3.7-.5 5.7 7.6-.6.5-1.8-2.4-16.9 12.8 1.8 2.4-.6.5-5.8-7.6.6-.4 1.8 2.2 8.4-6.4-6-7.9-8.4 6.4 1.7 2.3-.6.5-5.8-7.6.6-.4 1.9 2.4L57.9 212l-1.9-2.4.7-.5 5.7 7.6-.6.5-1.7-2.3-7.9 6 6 7.9zm4.5 22.9l-4-3.6 7.5-4.3zm-12.2 0l-2-1.8-.6.6 5.4 4.8.5-.6-2.5-2.2 6.5-3.9 4.4 4-3.1 6.8-2.5-2.2-.5.6 7.7 6.8.5-.6-2.2-1.9 9.4-21.7-.5-.4zm39.4 3.5l-2.7-1.2.3-.8 8.9 4.1-.4.7-2.8-1.3c-6.2 15-11.2 18.3-3.3 21.8s7.4-1.4 14.8-16.6l-3.1-1.4.3-.7 6.5 2.9-.4.8-2.4-1.2c-7.6 14.7-6.2 21.7-17.1 16.7s-5.1-7.8 1.4-23.8zm25.1 10.1l-2.9-.6v-.7l7.2 1.3 8.1 18.2 3-15.2-3.4-.7v-.7l7.3 1.4-.2.7-2.9-.5-4.2 21.8h-.7l-10.7-24.2-3.9 20.1 3.4.7v.8l-7.3-1.4v-.8l2.9.6zm27 3.9h-3v-.8h9.6v.8h-3v21.2h3v.8h-9.6v-.8h3zm12.2-.7l-2.6.4v-.8l9.6-1.5v.7l-3.2.6 7.9 15.7h.1l2.9-17.5-3.3.5v-.8l6.7-1.1v.8l-2.3.4-4.1 23.4h-.7zm23.9-4.9l-2.8 1.1-.3-.7 17-6.7 2.7 6.4-.7.3c-3-4.9-4.3-5-11.1-2.3l-1.5.6 3.7 9.2 1.6-.6c3.4-1.4 3.2-2.8 1.9-6l.9-.4 4 10.2-.9.3c-1.5-3.7-2.1-4.6-5.6-3.2l-1.6.6 3.8 9.6 4.5-1.7c4.6-1.8 5.2-4.7 4.1-9.2l.8-.3 2.6 7.4-17.8 7-.3-.7 2.8-1.1zm25.1-12.2c.9-.3 4.2-4.5 7.6.6s-1.8 6.5-2.4 7.3zm8.6 19.7l-2.5 1.7.4.6 8-5.2-.4-.7-2.4 1.6-6-9 1.7-1.1c3.4-2.2 4.8-1.5 7.3 1.9s3.8 4.7 7 2.5l2-1.3-.5-.6-.7.4c-1.6 1.1-2.7-.2-4.7-2.9s-4.5-3.8-8.9-1.7c2.4-2 3.7-4.2 1.7-7.3-4.1-6.3-8.9-.2-16.6 4.4l.4.6 2.5-1.6zm14.9-18.6l.6-.6c6.6 5.8 14.6-2.2 10.2-6.6s-11.6 5.8-17.1.2c-3.7-3.6-1.7-10 5.8-12.7l3.7 3.4-.6.6c-3.1-2-5.7-2-7.8.1s-2.3 4-.5 5.8c4 4 11.1-6.2 17.1-.1 4.2 4.2 1 11.5-6.7 14.3zm5.2-27.3l-1.8 2.4-.6-.4 5.8-7.8.6.5-1.8 2.4 17.1 12.7 1.7-2.4.7.5-5.8 7.7-.6-.5 1.8-2.4zm10.5-15.7c0 1-4.9 5.4 2.3 9.5l-.4.8-6.6-3.3 9.3-18.1 6.5 3.3-.5.9c-2.7-1.3-6.2-1.7-7.7 1.2l-1.2 2.5 18.7 9.5 1.6-3.1.7.3-4.8 9.6-.7-.4 1.6-3.1zm18.5-18.8l-11.7 3-.7 2.6-.8-.2 2.7-9.8.7.2-.8 3.2 10.3-2.5-7.8-7-.8 3.1-.8-.2 1.7-6.5.8.2-.7 2.4 8.8 7.9 10.4 2.8.8-2.9.7.2-2.4 9.3-.8-.2.8-2.9zM64 89.5l-10.5 19.7a3.41 3.41 0 0 1-4.5 1.64h-.08L41.7 107l2.6-4.8 6.9 3.6 9.5-18zm-8.8-4.6l-17.7-9.3-2.5 4.8 17.6 9.4zm-13 15.9c-2.4 4.7-7.6 6.9-11.6 4.8S25.5 98 28 93.3s7.7-6.8 11.6-4.7 5.1 7.6 2.6 12.2zm-5.1-7.5a4.11 4.11 0 0 0-5.55 1.7.54.54 0 0 1-.05.11 4.31 4.31 0 0 0 1.6 5.8 4.21 4.21 0 0 0 5.66-1.81v-.09a4.1 4.1 0 0 0-1.51-5.6zm46.7-52.7l3.6-2.2-1.9-3.2-6.1 3.8-1.7-2.8-4.7 2.9 1.7 2.8-6.2 3.7 2 3.1 3.6-2.2a9.87 9.87 0 0 0 .6 8.7 9.7 9.7 0 1 0 9.1-14.6zM86 55c-2.1 1.3-5.1.1-6.7-2.6s-1.3-5.9.7-7.1 5-.1 6.7 2.6S88 53.8 86 55zm21.6-.6l-4.7 2.8-15.6-25.5 4.7-2.8 4.8 7.8 4.2-2.6 1.9 3.1-4.2 2.6zm53.8-39.3v9.2h-2v-9.2h-5.3v18.8h-10.8V20.2h8.3v-3.7h-13.9v17.7a3.5 3.5 0 0 0 3.6 3.3h12.8V45h5.3V28.2h2V45h5.2V15.1zm51 33.3c6 4 13 1.2 12.2-4.8l1.8 1.2 2.1-3.1-5.8-3.8 1.8-2.7-4.6-3-1.8 2.7-5.8-3.9-2 3.1 1.8 1.2c-5.9 1.7-5.6 9.2.3 13.1zm6.9-3.7c-2.5 3.8-8.6-.3-6.1-4.1s8.7.2 6.1 4.1zm19.4 8.2l-2.1 3.1-4.1-2.8-4.1 6.2-4.6-3 9.3-14.1 4.6 3.1-3.2 4.8zm-32.3-6.2l21.1 14.1-6.3 9.5-4.6-3 4.3-6.5-16.6-11zm68.3 47.6l-11.2-19.9-3.2 1.8 10.2 18.1-16.7 9.3-1.8-3.2 9.6-5.4-2.7-4.8-9.6 5.4-1.5-2.6 9.7-5.4-2.7-4.9-9.7 5.5-2.9-5.3-3.2 1.8 15.7 28.1 3.3-1.8-1.5-2.6 17.1-9.6a3.2 3.2 0 0 0 1.18-4.37z"
    />
    <path
      :fill="blue"
      d="M206.5 139h-22.1v9.3h-8.5v12.9h-26.2V139h-9.8v2.5c0 12.7-11.9 19.4-23.6 19.4h-1.2v-13.8h.7c5.6 0 9.8-2.9 9.8-6.8V139H99l-6.7 63.4 60.5 25.8 60.5-25.8zm-75.8 57.9h-2.2v-14.5h-4.2v-1.7c2.8 0 4.4-.6 4.7-3.7h1.7zm11.2.4c-3 0-4.6-1.9-4.7-4.8h2.3c0 1.8.8 2.8 2.6 2.8 3.4 0 3.4-5.6 3.5-7.7h-.1c-1.8 3.9-8.8 3.4-8.8-3.7 0-4.2 2.3-6.9 5.3-6.9 5.3 0 5.7 5 5.7 9.2s-.1 11.1-5.8 11.1zm16.3 0c-3.5 0-5.4-2.1-5.2-5.6h2.2c-.1 2.1.7 3.6 3 3.6s3.1-2.5 3.1-4.8-.5-4.7-3.3-4.7a2.7 2.7 0 0 0-2.7 1.8h-2l1.2-10.2h8.4v2h-6.7l-.8 5.9c2.7-2.8 8.2-1.7 8.2 4.9 0 3.5-1.9 7.1-5.4 7.1zm19.7-5.4h-1.8v5h-2.2v-5h-7.2v-2l7.4-12.9h2v12.9h1.8zm-32.6-8c0 2.1-.7 4.1-3.2 4.1s-3.1-2.4-3.1-4.4.6-4.6 3.1-4.6 3.2 2.8 3.2 4.9zm23.2 6l5.4-9.4v9.4z"
    />
    <path
      :fill="sky"
      d="M184.4 116.1h-8.5v15.3h8.5v3.9h21.7l-2.8-26.7h-18.9zm-82.2-7.5l-2.8 26.7h26.1v-26.7zm37.7 0h9.9v26.7h-9.9z"
    />
  </svg>
</template>

<script>
const colors = {
  black: "#231815",
  blue: "#005BAC",
  gray: "#C9CACA",
  gold: "#BE8915",
  sky: "#00AFEC",
  white: "#FFFFFF"
};

export default {
  name: "InhaEmblem",
  props: {
    theme: {
      type: String
    },
    size: {
      type: String,
      default: "192px"
    }
  },
  computed: {
    black() {
      const { theme } = this;
      return colors[theme] || colors.black;
    },
    blue() {
      const { theme } = this;
      return colors[theme] || colors.blue;
    },
    sky() {
      const { theme } = this;
      return colors[theme] || colors.sky;
    }
  }
};
</script>
