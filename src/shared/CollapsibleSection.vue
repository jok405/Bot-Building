<template>
    <div>
        <div class="header">
            <span v-if="open" @click="open != open" >&#x25B2;
                Collapse</span>
                <span v-if="!open" @click="open !=open" >&#x25BC; Expand</span>
        </div>
    </div>
</template>
