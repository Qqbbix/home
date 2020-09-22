<template>
<div class="container">
    <div class="heading-block border-bottom-0 my-4 center">
        <h3>ดาวน์โหลดเอกสาร</h3>
        <span></span>
    </div>
    <div>
        <b-table striped hover :items="items" :fields="fields">
            <template v-slot:cell(html)="data">
                <span v-html="data.value"></span>
            </template>
        </b-table>
    </div>
    <div class="clear"></div>
</div>
</template>

<script>
export default {
    data() {
        return {
            fields: [{
                key: 'date',
                label: 'วันที่'
            }, {
                key: 'name',
                label: 'เรื่อง'
            }, {
                key: 'html',
                label: 'ดาวน์โหลด'
            }, {
                key: 'notics',
                label: 'หมายเหตุ'
            }],
            items: [{
                    date: '19/9/2020',
                    name: 'เอกสารวิชาการ',
                    html: '<a download  href="./document/Featrue.pdf" >ดาวน์โหลด</a>',
                    notics: '-'
                },
                {
                    date: '21/9/2020',
                    name: 'ไฟล์ที่สอง',
                    html: '<a download  href="./document/ชื่อไฟล์ที่สอง.pdf" >ดาวน์โหลด</a>',
                    notics: 'อันที่สอง'
                },
            ]
        }
    }
}
</script>
