<template>
    <div class="p-10 font-inter">
        <HeaderComponent></HeaderComponent>
        <div class="grid grid-cols-3 mt-5">
            <div class="py-5 border-t-2 border-r-2 border-neutral-200 space-y-8">
                <PersonaliaComponent></PersonaliaComponent>
                <SkillsComponent></SkillsComponent>
                <LanguagesComponent></LanguagesComponent>
            </div>
            <div class="p-5 col-span-2 border-t-2 border-neutral-200 space-y-8">
                <StudiesComponent></StudiesComponent>
                <ExperiencesComponent></ExperiencesComponent>
            </div>
        </div>
    </div>
</template>
<script setup>
import HeaderComponent from '@/components/HeaderComponent.vue'
import PersonaliaComponent from '@/components/PersonaliaComponent.vue'
import SkillsComponent from '@/components/SkillsComponent.vue'
import LanguagesComponent from '@/components/LanguagesComponent.vue'
import StudiesComponent from '@/components/StudiesComponent.vue'
import ExperiencesComponent from '@/components/ExperiencesComponent.vue'
</script>
