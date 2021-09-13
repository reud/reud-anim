<script>
    import { getContext } from 'svelte';
    import { TABS } from './Tabs.svelte';

    const tab = {};
    const { registerTab, selectTab, selectedTab } = getContext(TABS);

    registerTab(tab);
</script>

<style>
    button {
        background: none;
        border: none;
        border-radius: 0;
        margin-left: 20px;
        margin-right: 20px;
        font-size: 24px;
        font-weight: 700;
        color: #8197a4;
    }

    .selected {
        border-bottom: 2px solid white;
        color: white;
    }
</style>

<button class:selected="{$selectedTab === tab}" on:click="{() => selectTab(tab)}">
    <slot></slot>
</button>