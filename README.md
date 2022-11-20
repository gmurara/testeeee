<!DOCTYPE html>
<head>    
    <meta http-equiv="content-type" content="text/html; charset=UTF-8" />
    
        <script>
            L_NO_TOUCH = false;
            L_DISABLE_3D = false;
        </script>
    
    <style>html, body {width: 100%;height: 100%;margin: 0;padding: 0;}</style>
    <style>#map {position:absolute;top:0;bottom:0;right:0;left:0;}</style>
    <script src="https://cdn.jsdelivr.net/npm/leaflet@1.6.0/dist/leaflet.js"></script>
    <script src="https://code.jquery.com/jquery-1.12.4.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/js/bootstrap.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.js"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/leaflet@1.6.0/dist/leaflet.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap.min.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap-theme.min.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.6.3/css/font-awesome.min.css"/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/python-visualization/folium/folium/templates/leaflet.awesome.rotate.min.css"/>
    
            <meta name="viewport" content="width=device-width,
                initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
            <style>
                #map_952bd6944af393581d754e4573d926d9 {
                    position: relative;
                    width: 100.0%;
                    height: 100.0%;
                    left: 0.0%;
                    top: 0.0%;
                }
            </style>
        
</head>
<body>    
    
            <div class="folium-map" id="map_952bd6944af393581d754e4573d926d9" ></div>
        
</body>
<script>    
    
            var map_952bd6944af393581d754e4573d926d9 = L.map(
                "map_952bd6944af393581d754e4573d926d9",
                {
                    center: [-27.570838, -50.6216109],
                    crs: L.CRS.EPSG3857,
                    zoom: 7.48,
                    zoomControl: true,
                    preferCanvas: false,
                }
            );

            

        
    
            var tile_layer_d3af911cc4504396dc6506a29c9f3b27 = L.tileLayer(
                "https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png",
                {"attribution": "Data by \u0026copy; \u003ca href=\"http://openstreetmap.org\"\u003eOpenStreetMap\u003c/a\u003e, under \u003ca href=\"http://www.openstreetmap.org/copyright\"\u003eODbL\u003c/a\u003e.", "detectRetina": false, "maxNativeZoom": 18, "maxZoom": 18, "minZoom": 0, "noWrap": false, "opacity": 1, "subdomains": "abc", "tms": false}
            ).addTo(map_952bd6944af393581d754e4573d926d9);
        
    
            var marker_5890b2aaec954691881b8a7829735891 = L.marker(
                [-26.8902, -49.08461],
                {}
            ).addTo(map_952bd6944af393581d754e4573d926d9);
        
    
            var icon_2c6b20b21ea9fceed3af1d8efe39074f = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_5890b2aaec954691881b8a7829735891.setIcon(icon_2c6b20b21ea9fceed3af1d8efe39074f);
        
    
        var popup_007d4464a585eda067160c871dc48a54 = L.popup({"maxWidth": 200});

        
            var html_92bfe176c601a874d161deba8d393a1d = $(`<div id="html_92bfe176c601a874d161deba8d393a1d" style="width: 100.0%; height: 100.0%;"><br><b>Centro:</b> CIB - Centro de Inovação de Blumenau</br><br><b>Gestora:</b>Instituto Gene</br><br><b>Especialidades:</b> <br>🏭 Eletro Metal Mecânico</br> <br>🏭 Têxtil</br> <br>🎭 Turismo</br>  <br>🛒 Comércio</br> <br>🩺 Saúde</br></br></div>`)[0];
            popup_007d4464a585eda067160c871dc48a54.setContent(html_92bfe176c601a874d161deba8d393a1d);
        

        marker_5890b2aaec954691881b8a7829735891.bindPopup(popup_007d4464a585eda067160c871dc48a54)
        ;

        
    
    
            marker_5890b2aaec954691881b8a7829735891.bindTooltip(
                `<div>
                     CIB - Centro de Inovação de Blumenau
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_fe074ec6e767ec649c81112f55e46a99 = L.marker(
                [-27.048659999999998, -48.876490000000004],
                {}
            ).addTo(map_952bd6944af393581d754e4573d926d9);
        
    
            var icon_6ea85c12e75327cfbd2b0daec162d74a = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "lightgray", "prefix": "glyphicon"}
            );
            marker_fe074ec6e767ec649c81112f55e46a99.setIcon(icon_6ea85c12e75327cfbd2b0daec162d74a);
        
    
        var popup_996bdc8013dbacf457e42ec2b64964ee = L.popup({"maxWidth": 200});

        
            var html_df3d1a75706030af5430c06a68410cd3 = $(`<div id="html_df3d1a75706030af5430c06a68410cd3" style="width: 100.0%; height: 100.0%;"><br><b>Centro:</b> 408lab</br><br><b>Gestora:</b>Em implantação</br><br><b>Especialidades:</b> <br>🏭 Moda</br> <br>🛒 Varejo</br> <br>🏭 Automação Industrial</br> <br>📖 Educação</br> <br>🩺 Saúde</br></br></div>`)[0];
            popup_996bdc8013dbacf457e42ec2b64964ee.setContent(html_df3d1a75706030af5430c06a68410cd3);
        

        marker_fe074ec6e767ec649c81112f55e46a99.bindPopup(popup_996bdc8013dbacf457e42ec2b64964ee)
        ;

        
    
    
            marker_fe074ec6e767ec649c81112f55e46a99.bindTooltip(
                `<div>
                     408lab
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_6d1969fe735a789474adbf9795276f0b = L.marker(
                [-27.09283, -52.66336999999999],
                {}
            ).addTo(map_952bd6944af393581d754e4573d926d9);
        
    
            var icon_fcb2e041fded8c8a7ce7c1f94d712371 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_6d1969fe735a789474adbf9795276f0b.setIcon(icon_fcb2e041fded8c8a7ce7c1f94d712371);
        
    
        var popup_58fd1ae13116ce8f561f92b3ddbceebc = L.popup({"maxWidth": 200});

        
            var html_54ba378c1abb3c814d4c2a82788bffc1 = $(`<div id="html_54ba378c1abb3c814d4c2a82788bffc1" style="width: 100.0%; height: 100.0%;"><br><b>Centro:</b> Pollen Parque Científico e Tecnológico</br><br><b>Gestora:</b>UNOCHAPECÓ</br><br><b>Especialidades:</b> <br>🌱 Agro</br> <br>🩺 Saúde</br> <br>🏭 Máquinas e Equipamentos</br> <br>💻 TIC</br></br></div>`)[0];
            popup_58fd1ae13116ce8f561f92b3ddbceebc.setContent(html_54ba378c1abb3c814d4c2a82788bffc1);
        

        marker_6d1969fe735a789474adbf9795276f0b.bindPopup(popup_58fd1ae13116ce8f561f92b3ddbceebc)
        ;

        
    
    
            marker_6d1969fe735a789474adbf9795276f0b.bindTooltip(
                `<div>
                     Pollen Parque Científico e Tecnológico
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_d1939dc33879bd16f135641bf88ff5e0 = L.marker(
                [-27.167579999999997, -51.52045],
                {}
            ).addTo(map_952bd6944af393581d754e4573d926d9);
        
    
            var icon_c2525f6b8356ce11d78a3a0696acc791 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_d1939dc33879bd16f135641bf88ff5e0.setIcon(icon_c2525f6b8356ce11d78a3a0696acc791);
        
    
        var popup_886ea034b3f1400194e9aaf84bd83fdb = L.popup({"maxWidth": 200});

        
            var html_2541da174068a759e462a57d04d59755 = $(`<div id="html_2541da174068a759e462a57d04d59755" style="width: 100.0%; height: 100.0%;"><br><b>Centro:</b> Polo de Inovação Vale do Rio do Peixe – Inovale</br><br><b>Gestora:</b>Centro de Inovação Vale do Rio do Peixe</br><br><b>Especialidades:</b> <br>🌱 Alimentos</br> <br>🩺 Engenharia Biomédica</br> <br>💡 Energias Renováveis</br></br></div>`)[0];
            popup_886ea034b3f1400194e9aaf84bd83fdb.setContent(html_2541da174068a759e462a57d04d59755);
        

        marker_d1939dc33879bd16f135641bf88ff5e0.bindPopup(popup_886ea034b3f1400194e9aaf84bd83fdb)
        ;

        
    
    
            marker_d1939dc33879bd16f135641bf88ff5e0.bindTooltip(
                `<div>
                     Polo de Inovação Vale do Rio do Peixe – Inovale
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_c2a44f5bff149179ccf59e39f462460c = L.marker(
                [-26.77686, -51.01565],
                {}
            ).addTo(map_952bd6944af393581d754e4573d926d9);
        
    
            var icon_9addfb9e9a59628ec1f26859b31c100b = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_c2a44f5bff149179ccf59e39f462460c.setIcon(icon_9addfb9e9a59628ec1f26859b31c100b);
        
    
        var popup_095861d53020fce1532ef470f4444d58 = L.popup({"maxWidth": 200});

        
            var html_3a055077ecead75377800d4317c9e4a6 = $(`<div id="html_3a055077ecead75377800d4317c9e4a6" style="width: 100.0%; height: 100.0%;"><br><b>Centro:</b> Inova Contestado</br><br><b>Gestora:</b>Prefeitura de Caçador
</br><br><b>Especialidades:</b> <br>🌱 Indústria florestal</br> <br>🌱 Alimentos</br> <br>🏭 Plástico</br> <br>🏭 Têxtil</br></br></div>`)[0];
            popup_095861d53020fce1532ef470f4444d58.setContent(html_3a055077ecead75377800d4317c9e4a6);
        

        marker_c2a44f5bff149179ccf59e39f462460c.bindPopup(popup_095861d53020fce1532ef470f4444d58)
        ;

        
    
    
            marker_c2a44f5bff149179ccf59e39f462460c.bindTooltip(
                `<div>
                     Inova Contestado
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_fc4e54194d389c99f0cc28b96602e492 = L.marker(
                [-27.54468, -48.50019],
                {}
            ).addTo(map_952bd6944af393581d754e4573d926d9);
        
    
            var icon_1432ed21b189c2bfb31a46e0d4792319 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_fc4e54194d389c99f0cc28b96602e492.setIcon(icon_1432ed21b189c2bfb31a46e0d4792319);
        
    
        var popup_469ef94b1b49f484ef23b5b1c83eb508 = L.popup({"maxWidth": 200});

        
            var html_a5f0e6dedb6b6570ed35081b3c5c0013 = $(`<div id="html_a5f0e6dedb6b6570ed35081b3c5c0013" style="width: 100.0%; height: 100.0%;"><br><b>Centro:</b> Associação Catarinense das Empresas de Tecnologia - ACATE</br><br><b>Gestora:</b>Associação Catarinense das Empresas de Tecnologia - ACATE</br><br><b>Especialidades:</b> <br>💸 Fintech</br> <br>📖 Edtech</br> <br>💡 Energia</br></br></div>`)[0];
            popup_469ef94b1b49f484ef23b5b1c83eb508.setContent(html_a5f0e6dedb6b6570ed35081b3c5c0013);
        

        marker_fc4e54194d389c99f0cc28b96602e492.bindPopup(popup_469ef94b1b49f484ef23b5b1c83eb508)
        ;

        
    
    
            marker_fc4e54194d389c99f0cc28b96602e492.bindTooltip(
                `<div>
                     Associação Catarinense das Empresas de Tecnologia - ACATE
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_d5cab38867d7c486d317a37ef14348fc = L.marker(
                [-27.21865, -49.64812],
                {}
            ).addTo(map_952bd6944af393581d754e4573d926d9);
        
    
            var icon_12221a83706c140485a165d9cc28fd51 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_d5cab38867d7c486d317a37ef14348fc.setIcon(icon_12221a83706c140485a165d9cc28fd51);
        
    
        var popup_ca17c208a9e4a0f70769fc39032cdae4 = L.popup({"maxWidth": 200});

        
            var html_682fe743a292791e9396dd277a1aee2c = $(`<div id="html_682fe743a292791e9396dd277a1aee2c" style="width: 100.0%; height: 100.0%;"><br><b>Centro:</b> Centro de Inovação Norberto Frahm - CINF</br><br><b>Gestora:</b>Centro de Inovação Norberto Frahm - CINF</br><br><b>Especialidades:</b> <br>🩺 Desenvolvimento Social</br> <br>💻 TIC</br> <br>💻 Gestão e Automação de Processos</br></br></div>`)[0];
            popup_ca17c208a9e4a0f70769fc39032cdae4.setContent(html_682fe743a292791e9396dd277a1aee2c);
        

        marker_d5cab38867d7c486d317a37ef14348fc.bindPopup(popup_ca17c208a9e4a0f70769fc39032cdae4)
        ;

        
    
    
            marker_d5cab38867d7c486d317a37ef14348fc.bindTooltip(
                `<div>
                     Centro de Inovação Norberto Frahm - CINF
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_99f4407125036eb0a3e29b22841eee90 = L.marker(
                [-27.02542, -51.14561],
                {}
            ).addTo(map_952bd6944af393581d754e4573d926d9);
        
    
            var icon_1069736c5d9a6b34eaff0029dd60019f = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_99f4407125036eb0a3e29b22841eee90.setIcon(icon_1069736c5d9a6b34eaff0029dd60019f);
        
    
        var popup_a87d23bf3885b3da74d068ca38513f3f = L.popup({"maxWidth": 200});

        
            var html_249c78022448e59236aeb66939344b62 = $(`<div id="html_249c78022448e59236aeb66939344b62" style="width: 100.0%; height: 100.0%;"><br><b>Centro:</b> Centro de Inovação Dante Martorano</br><br><b>Gestora:</b>Prefeitura de Videira</br><br><b>Especialidades:</b> <br>🌱 Agro</br> <br>🏭 Processamento de Alimentos</br> <br>🛌 Turismo</br></br></div>`)[0];
            popup_a87d23bf3885b3da74d068ca38513f3f.setContent(html_249c78022448e59236aeb66939344b62);
        

        marker_99f4407125036eb0a3e29b22841eee90.bindPopup(popup_a87d23bf3885b3da74d068ca38513f3f)
        ;

        
    
    
            marker_99f4407125036eb0a3e29b22841eee90.bindTooltip(
                `<div>
                     Centro de Inovação Dante Martorano
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_86c1781a51881d493741e4261b8601f1 = L.marker(
                [-26.4627, -49.12198],
                {}
            ).addTo(map_952bd6944af393581d754e4573d926d9);
        
    
            var icon_6fb087de3b43ff61f35cc82b483cdc60 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_86c1781a51881d493741e4261b8601f1.setIcon(icon_6fb087de3b43ff61f35cc82b483cdc60);
        
    
        var popup_52ae581617418715565e846e9d951a88 = L.popup({"maxWidth": 200});

        
            var html_77a9768089541d4da40083d8a2f5c0b8 = $(`<div id="html_77a9768089541d4da40083d8a2f5c0b8" style="width: 100.0%; height: 100.0%;"><br><b>Centro:</b> Novale Hub</br><br><b>Gestora:</b>Associação do Centro de Inovação Jaraguá do Sul</br><br><b>Especialidades:</b> <br>💻 TIC</br> <br>💡 Energia</br> <br>🏭 Eletrometalmecânica</br> <br>🏭 Químicos e novos materiais</br></br></div>`)[0];
            popup_52ae581617418715565e846e9d951a88.setContent(html_77a9768089541d4da40083d8a2f5c0b8);
        

        marker_86c1781a51881d493741e4261b8601f1.bindPopup(popup_52ae581617418715565e846e9d951a88)
        ;

        
    
    
            marker_86c1781a51881d493741e4261b8601f1.bindTooltip(
                `<div>
                     Novale Hub
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_a3e9f04c8537d6e83be66940460cf5a5 = L.marker(
                [-26.23589, -48.88243],
                {}
            ).addTo(map_952bd6944af393581d754e4573d926d9);
        
    
            var icon_c68c5129a039217e2af7d7d7a6144f45 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_a3e9f04c8537d6e83be66940460cf5a5.setIcon(icon_c68c5129a039217e2af7d7d7a6144f45);
        
    
        var popup_a9d085bcb1e1b683c9e950bc6d168ee4 = L.popup({"maxWidth": 200});

        
            var html_3facc58208676df4bcbc6b216a490b89 = $(`<div id="html_3facc58208676df4bcbc6b216a490b89" style="width: 100.0%; height: 100.0%;"><br><b>Centro:</b> Ágora Tech Park</br><br><b>Gestora:</b>Instituto Ágora de Ciência e Tecnologia</br><br><b>Especialidades:</b> <br>🩺 Saúde</br> <br>🏭 Indústria 4.0</br> <br>🏛 Cidades inteligentes</br></br></div>`)[0];
            popup_a9d085bcb1e1b683c9e950bc6d168ee4.setContent(html_3facc58208676df4bcbc6b216a490b89);
        

        marker_a3e9f04c8537d6e83be66940460cf5a5.bindPopup(popup_a9d085bcb1e1b683c9e950bc6d168ee4)
        ;

        
    
    
            marker_a3e9f04c8537d6e83be66940460cf5a5.bindTooltip(
                `<div>
                     Ágora Tech Park
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_63d7ace6025b85c1033a2e1ed0344bce = L.marker(
                [-28.679040000000004, -49.35522],
                {}
            ).addTo(map_952bd6944af393581d754e4573d926d9);
        
    
            var icon_cf4a0e12db01a4980167b26f61f9e39e = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "lightgray", "prefix": "glyphicon"}
            );
            marker_63d7ace6025b85c1033a2e1ed0344bce.setIcon(icon_cf4a0e12db01a4980167b26f61f9e39e);
        
    
        var popup_d60bf0198f2870aa1e05168b0e2df0c1 = L.popup({"maxWidth": 200});

        
            var html_d55810af5e3d1ca8653fee7c92b30c52 = $(`<div id="html_d55810af5e3d1ca8653fee7c92b30c52" style="width: 100.0%; height: 100.0%;"><br><b>Centro:</b> CRIO</br><br><b>Gestora:</b>Em implantação</br><br><b>Especialidades:</b> <br>🏭 Cerâmica</br> <br>🏭 Plásticos</br> <br>🏭 Moda</br></br></div>`)[0];
            popup_d60bf0198f2870aa1e05168b0e2df0c1.setContent(html_d55810af5e3d1ca8653fee7c92b30c52);
        

        marker_63d7ace6025b85c1033a2e1ed0344bce.bindPopup(popup_d60bf0198f2870aa1e05168b0e2df0c1)
        ;

        
    
    
            marker_63d7ace6025b85c1033a2e1ed0344bce.bindTooltip(
                `<div>
                     CRIO
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_3b0efa5658065575df0b7b9319a6373d = L.marker(
                [-28.470409999999998, -49.00092],
                {}
            ).addTo(map_952bd6944af393581d754e4573d926d9);
        
    
            var icon_9cbcd81f12485a226096d34efaac5ca2 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "lightgray", "prefix": "glyphicon"}
            );
            marker_3b0efa5658065575df0b7b9319a6373d.setIcon(icon_9cbcd81f12485a226096d34efaac5ca2);
        
    
        var popup_fac6f4d05378458d4f6f01f1341d399e = L.popup({"maxWidth": 200});

        
            var html_d7be6498a190700b82317521212064d3 = $(`<div id="html_d7be6498a190700b82317521212064d3" style="width: 100.0%; height: 100.0%;"><br><b>Centro:</b> Centro de Inovação de Tubarão</br><br><b>Gestora:</b>Em implantação</br><br><b>Especialidades:</b> <br>🩺 Saúde</br> <br>💡 Energias Renováveis</br> <br>🏛 Cidades Inteligentes</br></br></div>`)[0];
            popup_fac6f4d05378458d4f6f01f1341d399e.setContent(html_d7be6498a190700b82317521212064d3);
        

        marker_3b0efa5658065575df0b7b9319a6373d.bindPopup(popup_fac6f4d05378458d4f6f01f1341d399e)
        ;

        
    
    
            marker_3b0efa5658065575df0b7b9319a6373d.bindTooltip(
                `<div>
                     Centro de Inovação de Tubarão
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_31e9ed6e1e11499bcee4b79324d5d223 = L.marker(
                [-26.24792, -49.38215],
                {}
            ).addTo(map_952bd6944af393581d754e4573d926d9);
        
    
            var icon_065664ef73c90688b5839a87cc4df1cf = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "lightgray", "prefix": "glyphicon"}
            );
            marker_31e9ed6e1e11499bcee4b79324d5d223.setIcon(icon_065664ef73c90688b5839a87cc4df1cf);
        
    
        var popup_5f6ddaa4da8b3f7b46ba0326e1e6c3f0 = L.popup({"maxWidth": 200});

        
            var html_9fda324c39f1c98e730549f1c9bb6b0f = $(`<div id="html_9fda324c39f1c98e730549f1c9bb6b0f" style="width: 100.0%; height: 100.0%;"><br><b>Centro:</b> Centro de Inovação da Região do Planalto Norte</br><br><b>Gestora:</b>Em implantação</br><br><b>Especialidades:</b> <br>🏭 Metalmecânica e Automação</br> <br>💻 TIC</br> <br>🩺 Saúde</br> <br>🏭 Química e Materiais</br></br></div>`)[0];
            popup_5f6ddaa4da8b3f7b46ba0326e1e6c3f0.setContent(html_9fda324c39f1c98e730549f1c9bb6b0f);
        

        marker_31e9ed6e1e11499bcee4b79324d5d223.bindPopup(popup_5f6ddaa4da8b3f7b46ba0326e1e6c3f0)
        ;

        
    
    
            marker_31e9ed6e1e11499bcee4b79324d5d223.bindTooltip(
                `<div>
                     Centro de Inovação da Região do Planalto Norte
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_89043719c3d27261a259193202f29dd0 = L.marker(
                [-27.801479999999998, -50.3372],
                {}
            ).addTo(map_952bd6944af393581d754e4573d926d9);
        
    
            var icon_8c33692d62f8a4fc890e4da18224e0bc = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_89043719c3d27261a259193202f29dd0.setIcon(icon_8c33692d62f8a4fc890e4da18224e0bc);
        
    
        var popup_cc74819fbe8f5d163b0bdfadd3415fde = L.popup({"maxWidth": 200});

        
            var html_edc510b083a63b7181ffe023213bcc19 = $(`<div id="html_edc510b083a63b7181ffe023213bcc19" style="width: 100.0%; height: 100.0%;"><br><b>Centro:</b> Orion Parque Tecnológico</br><br><b>Gestora:</b>Instituto Orion</br><br><b>Especialidades:</b> <br>🩺 Saúde</br> <br>🌱 Agro</br> <br>🩺 Biotecnologia</br> <br>🏛 Governo</br> <br>🚛 Logística</br></br></div>`)[0];
            popup_cc74819fbe8f5d163b0bdfadd3415fde.setContent(html_edc510b083a63b7181ffe023213bcc19);
        

        marker_89043719c3d27261a259193202f29dd0.bindPopup(popup_cc74819fbe8f5d163b0bdfadd3415fde)
        ;

        
    
    
            marker_89043719c3d27261a259193202f29dd0.bindTooltip(
                `<div>
                     Orion Parque Tecnológico
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_67ba96cda3492dfe686432daa1d3c39b = L.marker(
                [-26.953129999999998, -48.72815],
                {}
            ).addTo(map_952bd6944af393581d754e4573d926d9);
        
    
            var icon_6600b40e1ed6f2bd4a00d8140a6e21da = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "lightgray", "prefix": "glyphicon"}
            );
            marker_67ba96cda3492dfe686432daa1d3c39b.setIcon(icon_6600b40e1ed6f2bd4a00d8140a6e21da);
        
    
        var popup_7f1a856cda6ace81c5d708cd2f0d9fde = L.popup({"maxWidth": 200});

        
            var html_8b4dc9ebcf5215657c358988309615a7 = $(`<div id="html_8b4dc9ebcf5215657c358988309615a7" style="width: 100.0%; height: 100.0%;"><br><b>Centro:</b> Centro Regional de Inovação</br><br><b>Gestora:</b>Em implantação</br><br><b>Especialidades:</b> <br>🚛 Logística</br> <br>🛌 Turismo</br> <br>🌱 Economia do Mar</br> <br>🏭 Indústria Naval</br> <br>🩺 Saúde</br></br></div>`)[0];
            popup_7f1a856cda6ace81c5d708cd2f0d9fde.setContent(html_8b4dc9ebcf5215657c358988309615a7);
        

        marker_67ba96cda3492dfe686432daa1d3c39b.bindPopup(popup_7f1a856cda6ace81c5d708cd2f0d9fde)
        ;

        
    
    
            marker_67ba96cda3492dfe686432daa1d3c39b.bindTooltip(
                `<div>
                     Centro Regional de Inovação
                 </div>`,
                {"sticky": true}
            );
        
</script>
