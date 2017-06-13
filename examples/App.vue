<template>
  <div class="container-fluid">
    <!--<logo></logo>-->
    <!--<get-start></get-start>-->
    <!--<usage></usage>-->
    <!--<attributes></attributes>-->
    <!--<methods></methods>-->
    <!--<footbar></footbar>-->
    <pure-usage></pure-usage>
  </div>
</template>

<script>
import Logo from './components/Logo'
import GetStart from './components/GetStart'
import Usage from './components/Usage'
import Attributes from './components/Attributes'
import Methods from './components/Methods'
import Footbar from './components/Footer'
import PureUsage from './components/PureUsage'
import './css/styles.jd.css'


export default {
  components: {
    Logo,
    GetStart,
    Usage,
    Attributes,
    Methods,
    Footbar,
    PureUsage,
  },
}
</script>
