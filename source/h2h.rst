Host to Host (H2H)
==================

Untuk melakukan transaksi Host to Host (H2H), mitra AxesPay dapat memilih salah satu dari 2 cara yang disediakan, yaitu XML-RPC dan HTTP POST.

.. **Parameter**
..
.. ========= ======
.. Parameter Type
.. ========= ======
.. REQUESTID integer
.. MSISDN    string
..
..
.. **HTTP POST**
..
.. Jika menggunakan cara HTTP POST, 

XML Inquiry
-----------

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


