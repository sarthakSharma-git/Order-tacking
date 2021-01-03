# Order-tacking
As per my view, I am giving tacking detail for an order 
It is in HTML CODE 
This is an coding for giving tacking detail order which is placed by the client
<ol class="progtrckr" data-progtrckr-steps="5">
    <li class="progtrckr-done">Order Processing</li><!--
 --><li class="progtrckr-done">Pre-Production</li><!--
 --><li class="progtrckr-done">In Production</li><!--
 --><li class="progtrckr-todo">Shipped</li><!--
 --><li class="progtrckr-todo">Delivered</li>
</ol>



And another this is in CSS
ol.progtrckr {
    margin: 0;
    padding: 0;
    list-style-type none;
}

ol.progtrckr li {
    display: inline-block;
    text-align: center;
    line-heigt;
}

ol.progtrckr[data-progtrckr-steps="2"] li { width: 49%; }
ol.progtrckr[data-progtrckr-steps="3"] li { width: 33%; }
ol.progtrckr[data-progtrckr-steps="4"] li { width: 24%; }
ol.progtrckr[data-progtrckr-steps="5"] li { width: 19%; }
ol.progtrckr[data-progtrckr-steps="6"] li { width: 16%; }
ol.progtrckr[data-progtrckr-steps="7"] li { width: 14%; }
ol.progtrckr[data-progtrckr-steps="8"] li { width: 12%; }
ol.progtrckr[data-progtrckr-steps="9"] li { width: 11%; }

ol.progtrckr li.progtrckr-done {
    color: black;
