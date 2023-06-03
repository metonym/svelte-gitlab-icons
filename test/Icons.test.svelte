<script lang="ts">
  import {
    Diagram,
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
    MachineLearning,
    CloudPod,
  } from "../lib";
  import Api from "../lib/Api.svelte";
</script>

<Diagram />
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
<MachineLearning />
<CloudPod />
