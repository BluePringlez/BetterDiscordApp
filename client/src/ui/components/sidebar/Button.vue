/**
 * BetterDiscord Sidebar Button Component
 * Copyright (c) 2015-present Jiiks/JsSucks - https://github.com/Jiiks / https://github.com/JsSucks
 * All rights reserved.
 * https://betterdiscord.net
 *
 * This source code is licensed under the MIT license found in the
 * LICENSE file in the root directory of this source tree.
*/

<template>
    <div class="bd-item" :class="{active: item.active}" @click="$emit('click', item.id)">
        {{item.text}}
    </div>
</template>

<script>
    export default {
        props: ['item']
    }
</script>
