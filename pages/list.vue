<template>
    <div>
        <p>aaaa</p>
        <b-button>{{ hoge }}</b-button>
    </div>
</template>

<script lang="ts">
import { Component, Vue } from 'nuxt-property-decorator'

@Component({})
export default class List extends Vue {
    hoge:string = "aaaaaaaaaaaaa"

    get hogea() {
        return "a"
    }
}
</script>
