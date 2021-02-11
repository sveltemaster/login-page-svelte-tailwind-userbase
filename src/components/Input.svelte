<script>
    export let label
    export let value
</script>

<div class="relative mb-4">
    <label for={label} class="leading-7 text-sm text-gray-600">{label}</label>
    <input bind:value id={label} name={label} {...$$restProps}
        class="w-full bg-white rounded border border-gray-300 focus:border-pink-500 focus:ring-2 focus:ring-pink-200 text-base outline-none text-gray-700 py-1 px-3 leading-8 transition-colors duration-200 ease-in-out">
</div>