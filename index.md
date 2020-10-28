Bookings 
<script type="text/javascript">

if (typeof(window.Appointy) === 'undefined') {
window.Appointy = {};
}
window.Appointy.config = {

business: 'cityzenbrisbane',

defaultTab: 'Schedule',
extraParameter: '',
buttonImg: '',
modal: {
    height: '100%',
    width: '100%'
}

};
jQuery(document).ready(function() {

jQuery("#bookAppointy").click(function(){
    jQuery("#app-widget-btn").click();
    return false;
});

});

</script>
<script type="text/javascript" src="https://cdn.appointy.com/web/blob-web/js/appointy-widget.js"></script>
