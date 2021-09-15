<script lang="ts">
import { Tabs, TabList, TabPanel, Tab } from '../components/tabs/tabs.ts';
import DetailView from "./DetailView.svelte";
import ReviewVIew from "./ReviewVIew.svelte";
</script>

<Tabs>
    <div class="centering">
        <TabList >
            <Tab>エピソード</Tab>
            <Tab>関連タイトル</Tab>
            <Tab>詳細</Tab>
        </TabList>
    </div>


    <TabPanel>
        <h3 class="episodes">エピソード(0)</h3>
        <span style="color: white"> TODO review view はここではないので後で消す。テストのために一時的に表示</span>
        <ReviewVIew />
    </TabPanel>

    <TabPanel>
        <h3 class="episodes">特にありません・・・・</h3>
    </TabPanel>

    <TabPanel>
        <DetailView />
        <ReviewVIew />
    </TabPanel>
</Tabs>

<style>
    .centering {
        display: grid;
        place-content: center;
    }
</style>