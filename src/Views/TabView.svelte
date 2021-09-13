<script lang="ts">
import { Tabs, TabList, TabPanel, Tab } from '../components/tabs/tabs.ts';
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
    </TabPanel>

    <TabPanel>
        <h3 class="episodes">特にありません・・・・</h3>
    </TabPanel>

    <TabPanel>
        <h3 class="episodes">詳細</h3>
    </TabPanel>
</Tabs>

<style>
    .centering {
        display: grid;
        place-content: center;
    }
    .episodes {
        color: white;
        font-size: 20px;
        margin-top: 20px;
    }
</style>