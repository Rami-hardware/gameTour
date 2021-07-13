<template lang="pug">
    div 
        b-row
            b-col
                h4 learn more
                each val in ['About','Services','The Team','Advisors & Investors','Jobs']
                    ul
                        li=val
            b-col
                h4 contact us
                each val in ['Business Inquiries','Organizer and Player Support','Help Center','Media Kit']
                    ul
                        li=val
</template>

<script>
export default {
    name:'foot'
}
</script>