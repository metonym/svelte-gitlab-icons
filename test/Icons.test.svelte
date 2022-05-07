<script lang="ts">
  import {
    Fire,
    MergeRequestOpen,
    Connected,
    AttentionSolid,
    LicenseSm,
  } from "../lib";
  import Api from "../lib/Api.svelte";
</script>

<Fire />
<MergeRequestOpen />
<Api width="30" />
<Connected />
<AttentionSolid />
<LicenseSm fill="red" />
