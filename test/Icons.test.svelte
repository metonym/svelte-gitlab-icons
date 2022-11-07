<script lang="ts">
  import {
    Fire,
    MergeRequestOpen,
    Connected,
    AttentionSolid,
    LicenseSm,
    FaceNeutral,
    LiveStream,
    IssueTypeTask,
    EntityBlocked,
    CheckSm,
    Gitea,
  } from "../lib";
  import Api from "../lib/Api.svelte";
</script>

<Fire />
<MergeRequestOpen />
<Api width="30" />
<Connected />
<AttentionSolid />
<LicenseSm fill="red" />
<FaceNeutral />
<LiveStream />
<IssueTypeTask />
<EntityBlocked />
<CheckSm />
<Gitea />
