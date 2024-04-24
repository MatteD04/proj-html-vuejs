<script>
export default {
    name: 'InfoCompany',
    props: ['info','title','info2','info3','info4','info5']
}
</script>

<template>
    <div class="background-000">
        <div class="info-footer">
            <div>
                <h1>{{ title }}</h1>
                <ul>
                    <li>{{ info }}</li>
                    <li>{{ info2 }}</li>
                    <li>{{ info3 }}</li>
                    <li>{{ info4 }}</li>
                    <li>{{ info5 }}</li>
                </ul>
            </div>
        </div>
    </div>
</template>

<style scoped lang="scss">
.info-footer{
    width: 1100px;
    display: flex;
    li:hover{
        color: #f2870c;
    }
}
</style>