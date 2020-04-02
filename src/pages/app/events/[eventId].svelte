<script>
    import {url} from "@sveltech/routify";
    export let eventId;
</script>

<h1>Event details for event {eventId}</h1>

<p>
    <a href="{$url('/app/campaigns')}">Campaigns index</a>
</p>

<p>
    <a href="{$url('/app/campaigns/new/:eventId', { eventId: eventId })}">New
        campaign</a>
</p>
