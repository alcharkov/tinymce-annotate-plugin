#TinyMCE Annotate
Contributors: xyulex
Tags: tinymce, tiny mce, tiny, advanced, note, notes, annotate, annotation, annotations, plugin, post
Requires at least: 3.0
Tested up to: 4.2.2
Stable tag: 0.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=raulmartinez911%40hotmail%2ecom&item_name=TinyMCEAnnotateDonation &no_note=0&currency_code=EUR&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHostedGuest

Create annotations in your content with this TinyMCE plugin.

## Setup
Code example:
tinymce.init({
    selector: "#textarea",
    plugins: "tma_annotate",
    toolbar1: "tma_annotate | tma_annotatedelete | tma_annotatehide"
});
