.. AxesPay documentation master file, created by
   sphinx-quickstart on Wed Aug 30 10:44:56 2017.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

AxesPay API
===========

.. .. toctree::
..    :maxdepth: 2
..    :caption: Contents:
..
..
..
.. Indices and tables
.. ==================
..
.. * :ref:`genindex`
.. * :ref:`modindex`
.. * :ref:`search`


H2H Inquiry Request
-------------------

.. code-block:: xml

   <?xml version="1.0"?>
   <methodCall>
     <methodName>topUpRequest</methodName>
     <params>
       <param>
         <value>
           <struct>
             <member>
               <name>REQUESTID</name>
               <value><string>12495344</string></value>
             </member>
             <member>
               <name>MSISDN</name>
               <value><string>utdtronik</string></value>
             </member>
             <member>
               <name>PIN</name>
               <value><string>2266</string></value>
             </member>
             <member>
               <name>NOHP</name>
               <value><string>0247606920:TJASTEL</string></value>
             </member>
             <member>
               <name>NOM</name>
               <value><string>TJASTEL</string></value>
             </member>
           </struct>
         </value>
       </param>
     </params>
   </methodCall>
