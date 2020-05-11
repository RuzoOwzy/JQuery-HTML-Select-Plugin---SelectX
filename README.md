# JQuery-HTML-Select-Plugin---SelectX
This is a lightweight jquery select plugin( SelectX ) that works similar to native HTML Select element but with capability to inline filter the options

How to use it

        <script type="text/javascript" src="https://code.jquery.com/jquery-3.5.1.js"></script>
        <script type="text/javascript" src="<Path to SelectX Jquery Plugin>/SelectX.js"></script>
        <script type="text/javascript">
            $(document).ready(function () {
                try {
                     $("#selCountries").selectX();
                } catch (ex) { console.log(ex.message); }
            });
        </script>
        
        
        <select id="selCountries"></select>
        
        
Other SelectX functionalities are:
1. $("#selCountries").focusSelectX(); // When you want to focus the selectX enabled element
2. $("#selCountries").reloadSelectX(); // When the visible options of '#selCountries' have changed
3. $("#selCountries").updateSelectX(triggerChanges); // When you want to programmatically select the option of '#selCountries'
