<template>
  <f7-page pull-to-refresh @ptr:refresh="onRefresh">
    <f7-navbar :title="$root.config.title" />
    <f7-block inner inset>{{$lang('text')}}</f7-block>
    <f7-block inner inset>Funzia!</f7-block>
    <f7-block inner inset>
        <a class="link" href="https://tools.blankwebagency.com/index.php/audit">
            <i class="icon"></i>
            <span>Fai un Audit</span>
        </a>
    </f7-block>
        <f7-block inner inset>
            <a class="link" href="/audit/">
                <f7-icon material="open_in_browser" size="18" style="padding-bottom: 3px" />
                <span>Fai un Audit</span>
            </a>
        </f7-block>
    <f7-block>
      <f7-button big fill raised bg="green" href="https://github.com/scriptPilot/app-framework/blob/master/DOCUMENTATION.md" external>Documentation</f7-button>
    </f7-block>
  </f7-page>
</template>
