<script>
export default {
    methods: {
        randomColor() {
            return "#" + Math.floor(Math.random() * 0x1000000).toString(16)
        }
    },
}
</script>