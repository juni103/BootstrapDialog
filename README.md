# BootstrapDialog
Bootstrap 4 Dialog


#### Options
<b>attrs</b>: (obj-properties) attributes to attach with dialog dom </br>
<b>title</b>: (html|simple string) dialog title heading </br>
<b>message</b>: (html|simple string) body of the dialog </br>
<b>isFullScreen</b>: (boolean) to initialize as to cover body </br>
<b>showLoader</b>: (boolean) Show loader at dialog load </br>
<b>showHeaderBar</b>: (boolean|string|html) to show a bar after dialog title </br>
<b>hideFooter</b>: (boolean) to hide footer containing buttons </br>
<b>buttons</b>: see button options below </br>
<b>onShowDialog</b>: (params: dialog, event) bootstrap dialog show.bs.modal callback </br>
<b>onShownDialog</b>: (params: dialog, event) bootstrap dialog shown.bs.modal callback </br>
<b>onHideDialog</b>: (params: dialog, event) bootstrap dialog hide.bs.modal callback </br>
<b>onHiddenDialog</b>: (params: dialog, event) bootstrap dialog hidden.bs.modal callback </br>

#### Button Options
<b>id</b>: id attribute for the button </br>
<b>type</b>: (string) dismiss - to handle bootstrap dialog dismiss feature to close dialog </br>
<b>text</b>: (string) button text </br>
<b>cssClass</b>: (string) button css class(s) </br>
<b>click</b>: (params: dialog, event) </br>

#### Dialog Methods
dialog = DIALOG.show({...}) OR param passed to callbacks </br>
i.e dialog.updateBody(function(dialog){ return ...dialog-body }) </br>
<b>updateBody</b>: (params: dialog) to update the dialog body </br>
<b>updateHeaderBar</b>: (params: dialog) to update header bar </br>
<b>hide</b>: (params:void) to hide dialog </br>
<b>showLoader</b>: (params:void) to show dialog loader </br>
<b>hideLoader</b>: (params:void) to hide dialog loader </br>
<b>getButton</b>: (params:string) get dialog button from footer by its id </br>
