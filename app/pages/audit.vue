<template>
    <f7-page pull-to-refresh @ptr:refresh="onRefresh">
        <div data-page="PAGENAME">
            <f7-navbar :title="$root.config.title" />
            <f7-block>
                <div class="page-content ">
                    <div id="PAGEPlaceHolder"></div>
                </div>
            </f7-block>
        </div>
    </f7-page>
</template>
<!--
<script>
    myApp.onPageInit('PAGENAME', function (page) {

        $$.get('https://tools.blankwebagency.com/index.php/audit', {}, function (data) {
            $$('#PAGEPlaceHolder').html(data);
        });
    });
</script>
-->
