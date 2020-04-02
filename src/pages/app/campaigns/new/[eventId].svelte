<script>
    import {url} from "@sveltech/routify";

    export let eventId;
</script>

<h1>NEW campaign</h1>

<h2>{eventId}</h2>

<p>
    <a href="{$url('/')}">Back to home</a>
</p>

<p>
    <a href="{$url('/app/campaigns')}">Back to campaigns index</a>
</p>

<svelte:head>
    <title>New campaign</title>
</svelte:head>