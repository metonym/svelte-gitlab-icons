<script lang="ts">
  import {
    Building,
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
    Discord,
  } from "../lib";
  import Api from "../lib/Api.svelte";
</script>

<Building />
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
<Discord />
