<template>
    <section id="profile" class="py-5">
        <div class="row">
            <div class="col-sm-4">
                <img src="@/../resource/halchan_avater.png" alt="はるちゃんの写真" class="img-fluid rounded-circle" id="haru-image">
            </div>
            <div class="col-sm-8">
                <h2>はるちゃん<small>@hal_cha_n</small></h2>
                <h3>「こんにちは、はるちゃんです。」</h3>
                <p>ソフトウェア技術系VTuber。プログラミングの配信で人を集めてとことんゲームを見せつける詐欺師。お部屋を綺麗にする整頓王とも。得意分野はパズル・シミュレーション・Git・Swift・部屋掃除。</p>
            </div>
        </div>
    </section>
</template>
  
<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
    name: 'ProfileSection'
});
</script>
  