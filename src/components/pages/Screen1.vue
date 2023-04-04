<template>
  <DropZone ncBgType="bgColor" backgroundImage="" id="95d0bc6b-c588-436f-b212-3c361f727475"
    v-bind:style="{'width':'100%','height':'auto'}">
    <WAlert v-bind:fade="false" v-bind:pill="false" show="false" size="md" v-bind:isLink="false" v-bind:squared="false"
      hrefLink="" alertLabel="This alert will dismiss after time lapse" background="#17a2b8"
      buttonLabel="Show alert with count-down timer" v-bind:dismissible="false" alertVariant="warning"
      dismissLabel="Close" ncTypography="body1" verticalWidth="60px" buttonsVariant="info"
      v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'buttonLabel','displayName':'ButtonLabel'},{'type':'string','propName':'alertLabel','displayName':'AlertLabel'}]}"
      verticalHeight="60px" horizontalWidth="" progressVariant="warning" v-bind:dismissCountDown="5" horizontalHeight=""
      ncClickFontColor="#FFFFFF" ncFocusFontColor="#FFFFFF" ncHoverFontColor="#FFFFFF" ncClickBorderColor="#17a2b8"
      ncFocusBorderColor="#17a2b8" ncHoverBorderColor="#17a2b8" ncClickBackgroundColor="#17a2b8"
      ncFocusBackgroundColor="#17a2b8" ncHoverBackgroundColor="#17a2b8" position="relative"
      id="fc1372df-4d63-49b6-9406-a8a57a840484"
      v-bind:style="{'color':'#FFFFFF','width':'100%','height':'100%','tabIndex':'0px','boxShadow':'','fontStyle':'normal','marginTop':'0px','textAlign':'left','fontFamily':'Roboto-Regular,Roboto','fontWeight':'400','lineHeight':'24px','marginLeft':'0px','paddingTop':'0px','textShadow':'','visibility':'visible','borderColor':'#fff3cd','borderStyle':'none','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','textDecoration':'none','borderLeftWidth':'0px','borderRightWidth':'0px','horizontalHeight':'','borderBottomWidth':'0px','borderTopLeftRadius':'0px','borderTopRightRadius':'0px','borderBottomLeftRadius':'0px','borderBottomRightRadius':'0px','zIndex':2}"/>
  </DropZone>
</template>
<script>
export default {
  name: 'Screen1',
  data() {
    return {};
  },
  props: {},
  created() {},
  mounted() {},
  computed: {},
  methods: {},
  watch: {},
};
</script>

<style lang="scss" scoped>
@media (min-width: 1024.05px){[id='95d0bc6b-c588-436f-b212-3c361f727475'] {
             display: grid; 
             grid-template-columns: 31.044921875rem 20.703125rem 48.251953125rem;
             grid-template-rows: minmax(20.68359375rem, max-content) minmax(2.96875rem, max-content) minmax(59.16015625rem, max-content);
          }
[id='fc1372df-4d63-49b6-9406-a8a57a840484']{
          grid-area: 2/2/3/3;
          font-size: Max(Min(16rem, 12px),1.25rem);
          
          }}

@media (min-width: 768.05px) and (max-width: 1024px){[id='95d0bc6b-c588-436f-b212-3c361f727475'] {
             display: grid; 
             grid-template-columns: 37.060546875rem 25.87890625rem 37.060546875rem;
             grid-template-rows: minmax(25.8544921875rem, max-content) minmax(3.7109375rem, max-content) minmax(3.125rem, max-content);
          }
[id='fc1372df-4d63-49b6-9406-a8a57a840484']{
          grid-area: 2/2/3/3;
          font-size: Max(Min(16rem, 12px),1.5625rem);
          
          }}

@media (min-width: 480.05px) and (max-width: 768px){[id='95d0bc6b-c588-436f-b212-3c361f727475'] {
             display: grid; 
             grid-template-columns: 32.74739583333333rem 34.505208333333336rem 32.74739583333333rem;
             grid-template-rows: minmax(34.47265625rem, max-content) minmax(4.947916666666667rem, max-content) minmax(4.166666667rem, max-content);
          }
[id='fc1372df-4d63-49b6-9406-a8a57a840484']{
          grid-area: 2/2/3/3;
          font-size: Max(Min(16rem, 12px),2.0833333333333335rem);
          
          }}

@media (min-width: 375.05px) and (max-width: 480px){[id='95d0bc6b-c588-436f-b212-3c361f727475'] {
             display: grid; 
             grid-template-columns: 22.395833333333332rem 55.208333333333336rem 22.395833333333332rem;
             grid-template-rows: minmax(55.15625rem, max-content) minmax(7.916666666666667rem, max-content) minmax(5rem, max-content);
          }
[id='fc1372df-4d63-49b6-9406-a8a57a840484']{
          grid-area: 2/2/3/3;
          font-size: Max(Min(16rem, 12px),3.3333333333333335rem);
          
          }}

@media (min-width: 0px) and (max-width: 375px){[id='95d0bc6b-c588-436f-b212-3c361f727475'] {
             display: grid; 
             grid-template-columns: 6.4rem 87.2rem 6.4rem;
             grid-template-rows: minmax(70.6rem, max-content) minmax(12.504150943396226rem, max-content) minmax(6.4rem, max-content);
          }
[id='fc1372df-4d63-49b6-9406-a8a57a840484']{
          grid-area: 2/2/3/3;
          font-size: Max(Min(16rem, 12px),5.264905660377358rem);
          
          }}
</style>