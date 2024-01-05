<script lang="ts">
import { defineComponent } from 'vue'

import { UTable } from '#components'
export default defineComponent({
  extends: UTable,
  setup(props, ctx) {
    const attrs = UTable.setup ? UTable.setup(props, ctx) : {}
    return {
      ...attrs
    }
  }
})
</script>
