<template>
    <div>
        <input v-model="url" placeholder="Enter a URL" />
        <button @click="scan">Scan</button>
        <div v-if="results">
            <h2>Traffic: {{ results.traffic }}</h2>
            <h2>Bandwidth: {{ results.bandwidth }}</h2>
            <h2>TCP/IP: {{ results.tcpip }}</h2>
            <h2>Packets: {{ results.packets }}</h2>
        </div>
    </div>
</template>

<script>
import axios from 'axios';

export default{
    
}
</script>