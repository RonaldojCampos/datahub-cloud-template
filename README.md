---
datapackage:
  title: Dataset Template
  description: A template for a dataset to publish on DataHub. Uses the Data Package metadata.
  licenses:
  - path: http://opendatacommons.org/licenses/pddl/
    title: Open Data Commons Public Domain Dedication and License v1.0
  resources:
  - path: corporate-investment-in-artificial-intelligence-by-type.csv
    title: Annual global corporate investment in IA
    name: corporate-investment-in-artificial-intelligence-by-type
    format: csv
    schema:
      fields:
      - name: Entity
        type: Entity
      - name: Year
        type: Year
      - name: Total corporate investment - inflation adjusted
        type: Total corporate investment - inflation adjusted
---

Here's some text.

You can add as much text as you like.

The data files will be automatically displayed here.

We can add a chart:

<Map
                autoZoomConfiguration={{
                    layerName: 'Points'
                }}
                center={{
                    latitude: 53.9614,
                    longitude: -1.0739
                }}
                layers={[
                    {
                        data: {
                            url: 'https://opendata.arcgis.com/datasets/9c58741995174fbcb017cf46c8a42f4b_25.geojson'
                        },
                        name: 'Points',
                        tooltip: {
                            propNames: [
                                'Location'
                            ]
                        }
                    }
                ]}
                title="Roads in York"

            />
            <Map
                autoZoomConfiguration={{
                    layerName: 'Points'
                }}
                center={{
                    latitude: 53.9614,
                    longitude: -1.0739
                }}
                layers={[
                    {
                        data: {
                            geojson: {
    "type": "FeatureCollection",
    "name": "e-scooter_parking_bays",
    "crs": { "type": "name", "properties": { "name": "urn:ogc:def:crs:OGC:1.3:CRS84" } },
    "features": [
    { "type": "Feature", "properties": { "OBJECTID": 1, "Location": "Millfield Lane", "WARD": "Hull Road", "ADDRESS": "2 Millfield Lane, York, YO10 3AD" }, "geometry": { "type": "Point", "coordinates": [ -1.055429957881787, 53.953900188025301 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 2, "Location": "Lowther Terrace", "WARD": "Micklegate", "ADDRESS": "10 Lowther Terrace, York, YO24 4AG" }, "geometry": { "type": "Point", "coordinates": [ -1.095690235562312, 53.955220851808413 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 3, "Location": "Marygate", "WARD": "Guildhall", "ADDRESS": "5 Frederic Street, York, YO30 7BJ" }, "geometry": { "type": "Point", "coordinates": [ -1.090909547285418, 53.96268907784097 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 4, "Location": "Art Gallery 2", "WARD": "Guildhall", "ADDRESS": "Exhibition Square Bus Stop ED - 32900118, St Leonards Place, York, YO1 7EP" }, "geometry": { "type": "Point", "coordinates": [ -1.085919117294253, 53.962601623137608 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 5, "Location": "Flaxman", "WARD": "Hull Road", "ADDRESS": "61 Alcuin Avenue, York, YO10 3TH" }, "geometry": { "type": "Point", "coordinates": [ -1.054425160019781, 53.956862274152726 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 6, "Location": "Alcuin Ave", "WARD": "Hull Road", "ADDRESS": "30 Allen Close, York, YO10 3TH" }, "geometry": { "type": "Point", "coordinates": [ -1.052929985606613, 53.957377015163033 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 7, "Location": "CC - West Offices", "WARD": "Micklegate", "ADDRESS": "Station Rise, York, YO1 6JP" }, "geometry": { "type": "Point", "coordinates": [ -1.088709233755555, 53.958211121635948 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 8, "Location": "YU - Grub", "WARD": "Hull Road", "ADDRESS": "8 Yarburgh Way, York, YO10 5HD" }, "geometry": { "type": "Point", "coordinates": [ -1.036994477321574, 53.953597121823861 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 9, "Location": "CC - Art Gallery 1", "WARD": "Guildhall", "ADDRESS": "Exhibition Square, Exhibition Sq, York, YO30 7BN" }, "geometry": { "type": "Point", "coordinates": [ -1.085658699600231, 53.962893001509642 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 10, "Location": "TH - Lawrence Street", "WARD": "Fishergate", "ADDRESS": "39 Lawrence Street, York, YO10 3BW" }, "geometry": { "type": "Point", "coordinates": [ -1.068125933335758, 53.954636242440436 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 11, "Location": "NE - Monkgate", "WARD": "Guildhall", "ADDRESS": "53 Monkgate, York, YO31 7PB" }, "geometry": { "type": "Point", "coordinates": [ -1.075661764259678, 53.964349285159905 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 12, "Location": "Change name to : 'TR - Taddy Road", "WARD": "Dringhouses & Woodthorpe", "ADDRESS": "Tadcaster Road Dringhouses, York, YO24 1QA" }, "geometry": { "type": "Point", "coordinates": [ -1.107159782180929, 53.939436066412703 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 13, "Location": "BO - Kingsway North", "WARD": "Clifton", "ADDRESS": "137 Kingsway North, York, YO30 6PS" }, "geometry": { "type": "Point", "coordinates": [ -1.094769810627163, 53.971538687614768 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 14, "Location": "CC - Piccadilly", "WARD": "Guildhall", "ADDRESS": "34 Piccadilly, York, YO1 9TU" }, "geometry": { "type": "Point", "coordinates": [ -1.078102395400204, 53.957163841610104 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 16, "Location": "CC - Middleton's Hotel", "WARD": "Micklegate", "ADDRESS": "16 Cromwell Road, York, YO1 6DU" }, "geometry": { "type": "Point", "coordinates": [ -1.084037968913491, 53.954674496226481 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 17, "Location": "Fishergate Shops", "WARD": "Fishergate", "ADDRESS": "3 Winterscale Street, York, YO10 4UA" }, "geometry": { "type": "Point", "coordinates": [ -1.075529363970801, 53.950911039484851 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 18, "Location": "NE - York Hospital", "WARD": "Guildhall", "ADDRESS": "1 Wigginton Road, York, YO31 8HG" }, "geometry": { "type": "Point", "coordinates": [ -1.082416846730249, 53.970489858537412 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 19, "Location": "TH - James Street Corner", "WARD": "Guildhall", "ADDRESS": "2 James Street, York, YO10 3FU" }, "geometry": { "type": "Point", "coordinates": [ -1.067813138023608, 53.954807653779284 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 20, "Location": "BO - Clifton Tree", "WARD": "Clifton", "ADDRESS": "16 Clifton, York, YO30 6AE" }, "geometry": { "type": "Point", "coordinates": [ -1.091617760427049, 53.966202401167173 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 21, "Location": "CC - Rougier Street", "WARD": "Micklegate", "ADDRESS": "43 Tanner Row, York, YO1 6JB" }, "geometry": { "type": "Point", "coordinates": [ -1.087226458158529, 53.958498838499033 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 22, "Location": "CC - Micklegate", "WARD": "Micklegate", "ADDRESS": "Partisan & the French House, 112 Micklegate, York, YO1 6JY" }, "geometry": { "type": "Point", "coordinates": [ -1.089808938475936, 53.956704276556252 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 23, "Location": "BO - Bootham Row Car Park", "WARD": "Guildhall", "ADDRESS": "5 St. Giles Court, York, YO31 7EB" }, "geometry": { "type": "Point", "coordinates": [ -1.085200615905823, 53.963896738486312 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 24, "Location": "Tang Hall Library", "WARD": "Heworth", "ADDRESS": "305 Fifth Avenue, York, YO31 0PS" }, "geometry": { "type": "Point", "coordinates": [ -1.048932962551252, 53.960289232397365 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 25, "Location": "YSJU City Centre Campus", "WARD": "Guildhall", "ADDRESS": "11 De Grey Terrace, York, YO31 7RB" }, "geometry": { "type": "Point", "coordinates": [ -1.082214409306074, 53.9655670535033 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 26, "Location": "YSJU SU", "WARD": "Guildhall", "ADDRESS": "York St John University, Lord Mayor's Walk, York, YO31 7EX" }, "geometry": { "type": "Point", "coordinates": [ -1.080815712579503, 53.965385323983604 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 27, "Location": "HR - YSJ Playing Fields", "WARD": "Huntington & New Earswick", "ADDRESS": "181 Haxby Road, York, YO32 4AB" }, "geometry": { "type": "Point", "coordinates": [ -1.074173875357817, 53.980229533384765 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 28, "Location": "YU - Wentworth College", "WARD": "Hull Road", "ADDRESS": "Wentworth Way, York, YO10 5NG" }, "geometry": { "type": "Point", "coordinates": [ -1.057707528137461, 53.946646207356054 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 29, "Location": "NE - City Residence", "WARD": "Guildhall", "ADDRESS": "Stab Alley, York, YO31 8JY" }, "geometry": { "type": "Point", "coordinates": [ -1.077452804365379, 53.970376375471254 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 30, "Location": "YU - Broadway", "WARD": "Fishergate", "ADDRESS": "55 Broadway, York, YO10 4JP" }, "geometry": { "type": "Point", "coordinates": [ -1.070596313600778, 53.941134308758997 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 31, "Location": "YU - Information Centre", "WARD": "Hull Road", "ADDRESS": "Information Centre, York, YO10 5DD" }, "geometry": { "type": "Point", "coordinates": [ -1.053734025342445, 53.948754313496536 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 32, "Location": "Ysju Music Block Alley", "WARD": "Guildhall", "ADDRESS": "York St John University, Lord Mayor's Walk, York, YO31 7EX" }, "geometry": { "type": "Point", "coordinates": [ -1.080836987226288, 53.965044171418022 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 33, "Location": "BR - Winning Post", "WARD": "Micklegate", "ADDRESS": "126 Bishopthorpe Road, York, YO23 1LA" }, "geometry": { "type": "Point", "coordinates": [ -1.085621089403902, 53.947777255275049 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 34, "Location": "BR - Campleshon", "WARD": "Micklegate", "ADDRESS": "12 Campleshon Road, York, YO23 1LG" }, "geometry": { "type": "Point", "coordinates": [ -1.086918193754237, 53.943733203340827 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 35, "Location": "PR - Point Zero Trampoline", "WARD": "Rural West York", "ADDRESS": "Energi York, York, YO26 6RU" }, "geometry": { "type": "Point", "coordinates": [ -1.127371874235908, 53.97531996424523 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 36, "Location": "PR - Poppleton Road", "WARD": "Holgate", "ADDRESS": "68 Poppleton Road, York, YO26 4QS" }, "geometry": { "type": "Point", "coordinates": [ -1.112238669324432, 53.959852153777007 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 37, "Location": "CC - Toft Green", "WARD": "Micklegate", "ADDRESS": "6 Toft Green, York, YO1 6JJ" }, "geometry": { "type": "Point", "coordinates": [ -1.091238089247406, 53.956599535934409 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 38, "Location": "BR - Roomzzz", "WARD": "Micklegate", "ADDRESS": "1 Terry Avenue, York, YO23 1FG" }, "geometry": { "type": "Point", "coordinates": [ -1.07975937242305, 53.951402814432271 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 39, "Location": "CC - St George's", "WARD": "Fishergate", "ADDRESS": "St Georges Field Car Park, Tower St, York, YO10 4BX" }, "geometry": { "type": "Point", "coordinates": [ -1.07978434023741, 53.954068914140713 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 40, "Location": "BO - Bootham Crescent", "WARD": "Clifton", "ADDRESS": "4 Bootham Crescent, York, YO30 7DQ" }, "geometry": { "type": "Point", "coordinates": [ -1.090721265763709, 53.96587165319243 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 41, "Location": "NE - Groves", "WARD": "Guildhall", "ADDRESS": "96 Lowther Street, York, YO31 7LZ" }, "geometry": { "type": "Point", "coordinates": [ -1.078902255224921, 53.967262713056158 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 42, "Location": "PR – Boroughbridge Road", "WARD": "Acomb", "ADDRESS": "214 Boroughbridge Road, York, YO26 6AY" }, "geometry": { "type": "Point", "coordinates": [ -1.132482269792107, 53.96959569654058 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 43, "Location": "PR - Texaco", "WARD": "Acomb", "ADDRESS": "87 Boroughbridge Road, York, YO26 5SZ" }, "geometry": { "type": "Point", "coordinates": [ -1.124309449077596, 53.965673339134447 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 44, "Location": "BO – Bella’s Kitchen", "WARD": "Clifton", "ADDRESS": "102 Clifton, York, YO30 6BA" }, "geometry": { "type": "Point", "coordinates": [ -1.095594167726741, 53.969035167087341 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 45, "Location": "TR – Moor Lane Youth Centre", "WARD": "Dringhouses & Woodthorpe", "ADDRESS": "100 Wains Road, York, YO24 2UL" }, "geometry": { "type": "Point", "coordinates": [ -1.121498846069083, 53.938506795283672 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 46, "Location": "TR – Vaccination Centre", "WARD": "Dringhouses & Woodthorpe", "ADDRESS": "Tesco Café, Askham Bar, Tadcaster Rd, York YO24 1QS" }, "geometry": { "type": "Point", "coordinates": [ -1.11409802599014, 53.933444477394048 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 47, "Location": "Hospital Fields Road", "WARD": "Fishergate", "ADDRESS": "6 Hospital Fields Road, York, YO10 4DZ" }, "geometry": { "type": "Point", "coordinates": [ -1.078681009367785, 53.945167675603955 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 48, "Location": "TH – Vita Student", "WARD": "Fishergate", "ADDRESS": "102 Lawrence Street, York, YO10 3FT" }, "geometry": { "type": "Point", "coordinates": [ -1.065684978136212, 53.954449708555003 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 49, "Location": "The Barbican", "WARD": "Fishergate", "ADDRESS": "28 Barbican Road, York, YO10 4NT" }, "geometry": { "type": "Point", "coordinates": [ -1.072373341624938, 53.953127498605987 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 50, "Location": "CC – Castle Car Park", "WARD": "Guildhall", "ADDRESS": "14 Tower Street, York, YO1 9WD" }, "geometry": { "type": "Point", "coordinates": [ -1.080113865980238, 53.95639281761143 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 51, "Location": "CC – Nelson’s Yard", "WARD": "Guildhall", "ADDRESS": "4 Dennis Street, York, YO1 9AA" }, "geometry": { "type": "Point", "coordinates": [ -1.077151362682217, 53.956595149726219 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 52, "Location": "NE – Monkbar Car Park", "WARD": "Guildhall", "ADDRESS": "14 High Newbiggin Street, York, YO31 7QS" }, "geometry": { "type": "Point", "coordinates": [ -1.079064800054747, 53.964054166998231 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 53, "Location": "Walmgate", "WARD": "Guildhall", "ADDRESS": "32 Margaret Street, York, YO1 9TR" }, "geometry": { "type": "Point", "coordinates": [ -1.073798151627066, 53.956052571856382 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 54, "Location": "Jorvik Crossfit", "WARD": "Heworth", "ADDRESS": "64 Hallfield Road, York, YO31 0UP" }, "geometry": { "type": "Point", "coordinates": [ -1.066208061184509, 53.960789664815962 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 55, "Location": "Mossdale Avenue", "WARD": "Heworth", "ADDRESS": "Mossdale Avenue, York, YO31 0LP" }, "geometry": { "type": "Point", "coordinates": [ -1.049452068931892, 53.964696990862507 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 56, "Location": "TH – Fifth Avenue", "WARD": "Heworth", "ADDRESS": "10 Fifth Avenue, York, YO31 0XW" }, "geometry": { "type": "Point", "coordinates": [ -1.067858893250118, 53.964219621533267 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 57, "Location": "TH – Sixth Avenue", "WARD": "Heworth", "ADDRESS": "21 Sixth Avenue, York, YO31 0UT" }, "geometry": { "type": "Point", "coordinates": [ -1.063315242336473, 53.962584917672878 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 58, "Location": "Acomb Road", "WARD": "Holgate", "ADDRESS": "Acomb Road, York, YO24 4EY" }, "geometry": { "type": "Point", "coordinates": [ -1.115848299860386, 53.95558076166833 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 59, "Location": "Garfield Corner", "WARD": "Holgate", "ADDRESS": "29 Garfield Terrace, York, YO26 4XL" }, "geometry": { "type": "Point", "coordinates": [ -1.10564853094826, 53.962740875020941 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 60, "Location": "Leeman Road 2", "WARD": "Holgate", "ADDRESS": "Howarth Timber & Building Supplies, Leeman Rd, York YO26 4ZH" }, "geometry": { "type": "Point", "coordinates": [ -1.10220938989781, 53.961816221410288 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 61, "Location": "PR – The Fox", "WARD": "Holgate", "ADDRESS": "169 Holgate Road, York, YO24 4DF" }, "geometry": { "type": "Point", "coordinates": [ -1.105389626036795, 53.955060709158303 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 62, "Location": "East Campus", "WARD": "Hull Road", "ADDRESS": "25 Hull Road, York, YO10 5GL" }, "geometry": { "type": "Point", "coordinates": [ -1.029205288345566, 53.949671173162756 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 63, "Location": "TH – Matmer House", "WARD": "Hull Road", "ADDRESS": "Pizza Hut, Matmer House, York YO10 3JW" }, "geometry": { "type": "Point", "coordinates": [ -1.058386621912596, 53.954219127482197 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 64, "Location": "TH – Melrosegate", "WARD": "Hull Road", "ADDRESS": "60 Alcuin Avenue, York, YO10 3TX" }, "geometry": { "type": "Point", "coordinates": [ -1.058931044860531, 53.956079465948434 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 65, "Location": "West Campus", "WARD": "Hull Road", "ADDRESS": "Harewood Way, York, YO10 5DD" }, "geometry": { "type": "Point", "coordinates": [ -1.051299890883546, 53.947976592664595 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 66, "Location": "YU – Alcuin Way", "WARD": "Hull Road", "ADDRESS": "Alcuin Way, York, YO10 5NY" }, "geometry": { "type": "Point", "coordinates": [ -1.048825159600908, 53.949408199344298 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 67, "Location": "YU – Church Lane", "WARD": "Hull Road", "ADDRESS": "6 Innovation Close, York, YO10 5ZF" }, "geometry": { "type": "Point", "coordinates": [ -1.04536280205439, 53.949465234420281 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 68, "Location": "YU – Halifax College", "WARD": "Hull Road", "ADDRESS": "Halifax College, Garrowby Way, York YO10 5DN" }, "geometry": { "type": "Point", "coordinates": [ -1.04750670748312, 53.941513649014375 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 69, "Location": "YU – James College", "WARD": "Hull Road", "ADDRESS": "19 Newton Way, York, YO10 5DE" }, "geometry": { "type": "Point", "coordinates": [ -1.054206389872136, 53.945095789212466 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 70, "Location": "YU – Sports Centre", "WARD": "Hull Road", "ADDRESS": "Sports & Fitness Centre, James Way, York YO10 5NA" }, "geometry": { "type": "Point", "coordinates": [ -1.055941530760825, 53.943925053369817 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 71, "Location": "Huntington Road – Old Village", "WARD": "Huntington & New Earswick", "ADDRESS": "82 The Old Village, Huntington, York, YO32 9QR" }, "geometry": { "type": "Point", "coordinates": [ -1.058416309068703, 53.999278480105254 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 72, "Location": "Huntington Road – Post Office", "WARD": "Huntington & New Earswick", "ADDRESS": "49 North Moor Road, Huntington, York, YO32 9QN" }, "geometry": { "type": "Point", "coordinates": [ -1.057177384012101, 53.997247778895805 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 73, "Location": "NE - HWMC", "WARD": "Huntington & New Earswick", "ADDRESS": "1 New Lane, Huntington, York, YO32 9NU" }, "geometry": { "type": "Point", "coordinates": [ -1.058872293256773, 53.99482632002718 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 74, "Location": "BR - Bishy Road corner", "WARD": "Micklegate", "ADDRESS": "Inner Ring Road, York, YO23 1YD" }, "geometry": { "type": "Point", "coordinates": [ -1.084531648328897, 53.952446277246629 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 75, "Location": "BR - St. Benedict Road", "WARD": "Micklegate", "ADDRESS": "31 St. Benedict Road, York, YO23 1BH" }, "geometry": { "type": "Point", "coordinates": [ -1.087942872553077, 53.952141534831455 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 76, "Location": "CC - Nunnery Lane Car Park", "WARD": "Micklegate", "ADDRESS": "Nunnery Lane Car Park, Nunnery Lane, York YO23 1JG" }, "geometry": { "type": "Point", "coordinates": [ -1.089128597408691, 53.954819209753715 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 77, "Location": "Tanners Moat", "WARD": "Micklegate", "ADDRESS": "Lendal Bridge, York, YO1 6HU" }, "geometry": { "type": "Point", "coordinates": [ -1.087976570821271, 53.959516397718147 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 78, "Location": "Rawcliffe Rec", "WARD": "Rawcliffe & Clifton Without", "ADDRESS": "51 St Mark's Grove, York, YO30 5NN" }, "geometry": { "type": "Point", "coordinates": [ -1.110919724646948, 53.986271562341635 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 79, "Location": "RC – Brunch", "WARD": "Rawcliffe & Clifton Without", "ADDRESS": "37 Auster Road, York, YO30 4XA" }, "geometry": { "type": "Point", "coordinates": [ -1.094083500927026, 53.98944108022846 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 80, "Location": "RC – Clifton Hotel", "WARD": "Rawcliffe & Clifton Without", "ADDRESS": "162 Water Lane, York, YO30 6QA" }, "geometry": { "type": "Point", "coordinates": [ -1.097266556581312, 53.976696434863811 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 81, "Location": "RC – Greystoke Road", "WARD": "Rawcliffe & Clifton Without", "ADDRESS": "53 Eastholme Drive, York, YO30 5SU" }, "geometry": { "type": "Point", "coordinates": [ -1.110515592251892, 53.981479139522008 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 82, "Location": "RC – Rawcliffe Lane", "WARD": "Rawcliffe & Clifton Without", "ADDRESS": "5 Malton Way, York, YO30 5SQ" }, "geometry": { "type": "Point", "coordinates": [ -1.102488633471057, 53.974880685359665 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 83, "Location": "RC – Salon Supplies", "WARD": "Rawcliffe & Clifton Without", "ADDRESS": "9 Bleriot Way, York, YO30 4WP" }, "geometry": { "type": "Point", "coordinates": [ -1.099233643013512, 53.989473674372285 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 84, "Location": "TR – Askham Bar", "WARD": "Dringhouses & Woodthorpe", "ADDRESS": "Tesco Petrol Station, Askham Bar, York, YO24 1QS" }, "geometry": { "type": "Point", "coordinates": [ -1.114340436980219, 53.933213321108823 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 85, "Location": "Great North Way", "WARD": "Rural West York", "ADDRESS": "62 Great North Way, Nether Poppleton, York, YO26 6RB" }, "geometry": { "type": "Point", "coordinates": [ -1.129878543400805, 53.977464322320657 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 86, "Location": "Clockhouse", "WARD": "Westfield", "ADDRESS": "22 Tudor Road, York, YO24 3BA" }, "geometry": { "type": "Point", "coordinates": [ -1.121485322440709, 53.951070709146002 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 87, "Location": "Gale Lane", "WARD": "Westfield", "ADDRESS": "117 Stuart Road, York, YO24 3AQ" }, "geometry": { "type": "Point", "coordinates": [ -1.123680775734822, 53.946049873792809 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 88, "Location": "Lidl Acomb", "WARD": "Westfield", "ADDRESS": "306 Thanet Road, York, YO24 2NW" }, "geometry": { "type": "Point", "coordinates": [ -1.121391146196771, 53.9441520623702 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 89, "Location": "Heworth Place", "WARD": "Heworth", "ADDRESS": "28 Heworth Road, York, YO31 0AE" }, "geometry": { "type": "Point", "coordinates": [ -1.06212244234781, 53.967181299558781 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 90, "Location": "Fulford Road - Opposite Aldi", "WARD": "Fishergate", "ADDRESS": "254 Fulford Road, York, YO10 4HD" }, "geometry": { "type": "Point", "coordinates": [ -1.073944873754617, 53.943548101367959 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 91, "Location": "Fulford Arms", "WARD": "Fishergate", "ADDRESS": "204-206 Fulford Road, York, YO10 4EG" }, "geometry": { "type": "Point", "coordinates": [ -1.073763399209508, 53.946760956066164 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 92, "Location": "The Boulevard Student Accommodation", "WARD": "Fishergate", "ADDRESS": "The Boulevard, York, Y010 3HD" }, "geometry": { "type": "Point", "coordinates": [ -1.060788866945753, 53.953931594787065 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 93, "Location": "Frederick House Student Accommodation", "WARD": "Fishergate", "ADDRESS": "121 Fulford Road, York, YO10 4EX" }, "geometry": { "type": "Point", "coordinates": [ -1.072950840205389, 53.946988381381651 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 94, "Location": "Navigation Road", "WARD": "Guildhall", "ADDRESS": "118 Navigation Road, York, YO1 9UL" }, "geometry": { "type": "Point", "coordinates": [ -1.072916002733438, 53.958205116295147 ] } },
    { "type": "Feature", "properties": { "OBJECTID": 95, "Location": "Clifton Green", "WARD": "Clifton", "ADDRESS": "3-5 Clifton Green, YO30 6BA" }, "geometry": { "type": "Point", "coordinates": [ -1.096225668522511, 53.969177109042768 ] } }
    ]
    }
                        },
                        name: 'Points',
                        tooltip: {
                            propNames: [
                                'Location'
                            ]
                        }
                    }
                ]}
                title="Roads in York"
            />


