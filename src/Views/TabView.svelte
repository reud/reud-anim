<script lang="ts">
import { Tabs, TabList, TabPanel, Tab } from '../components/tabs/tabs.ts';
</script>

<Tabs>
    <TabList>
        <Tab>エピソード</Tab>
        <Tab>関連タイトル</Tab>
        <Tab>詳細</Tab>
    </TabList>

    <TabPanel>
        <h2>First panel</h2>
    </TabPanel>

    <TabPanel>
        <h2>Second panel</h2>
    </TabPanel>

    <TabPanel>
        <h2>Third panel</h2>
    </TabPanel>
</Tabs>