<template>
    <button type="button" @click="$parent.execCommand('justifyLeft')">
        {{$parent.locale["left justify"]}}
    </button>
    <button type="button" @click="$parent.execCommand('justifyCenter')">
        {{$parent.locale["center justify"]}}
    </button>
    <button type="button" @click="$parent.execCommand('justifyRight')">
        {{$parent.locale["right justify"]}}
    </button>
</template>