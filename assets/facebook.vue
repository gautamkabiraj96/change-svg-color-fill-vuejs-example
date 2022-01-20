

<template>
  <div>
    <svg
      :fill="svgColor"
      version="1.1"
      baseProfile="tiny"
      id="Layer_1"
      xmlns:x="&ns_extend;"
      xmlns:i="&ns_ai;"
      xmlns:graph="&ns_graphs;"
      xmlns="http://www.w3.org/2000/svg"
      xmlns:xlink="http://www.w3.org/1999/xlink"
      xmlns:a="http://ns.adobe.com/AdobeSVGViewerExtensions/3.0/"
      x="0px"
      y="0px"
      width="42px"
      height="42px"
      viewBox="-0.5 0.5 42 42"
      xml:space="preserve"
    >
      <path
        d="M28.08,6.51c0.29-0.01,1.109-0.03,1.42-0.01c1.12,0,2.84-0.1,4,0v5h-4c-1.46,0-2,0.35-2,2v4h5v5h-5v14h-5v-14h-4v-5h4
	l-0.061-4.42c0-3.061,0.621-4.92,3.15-6.02C26.24,6.78,27.23,6.53,28.08,6.51z M0.5,1.5v39h39v-39H0.5z"
      />
    </svg>
  </div>
</template>

<script>
export default {
  name: "Facebook",
  props: ["svgColor"],
};
</script>