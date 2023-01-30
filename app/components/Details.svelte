<page> </page>

<script>
    import { FlickService } from "~/services/FlickService";
    export let flickId
    let flick = FlickService.getInstance().getFlickById(flickId)
</script>