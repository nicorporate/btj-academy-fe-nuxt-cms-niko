<template>
    <div>
        <p class="item my-4 p-4" @click="toAbout">About Me</p>
            <hr/>
        <p class="item my-4 p-4" @click="toEducation">Education</p>
            <hr/>
        <p class="item my-4 p-4" @click="toWork">Work Experience</p>
            <hr/>
        <p class="item my-4 p-4" @click="toMotto">Motto</p>

    </div>
</template>

<script>
export default {
    methods: {
        toAbout(){
            navigateTo('/admin/about')
        },
           toEducation(){
            navigateTo('/admin/education')
        },
           toWork(){
            navigateTo('/admin/work')
        },
           toMotto(){
            navigateTo('/admin/motto')
        },
    }
}
</script>

<style>


.sidebar {
    background-color: rgb(244, 244, 244);
    align-items: center;
    border-color:#2219dd;
    text-align: center;
}

.item {
    color: #8673f0;
}

.item:hover{
    color: white;
    background-color: #9682df;


}
hr {
    color: #4435e3;
}
</style>