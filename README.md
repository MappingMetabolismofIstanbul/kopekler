var config = {
    style: 'mapbox://styles/dogatmn/clyseydg9001201nu65sb3kb7',
    accessToken: 'pk.eyJ1IjoiZG9nYXRtbiIsImEiOiJjbHlyMTJmcXgwMjQ3MmtzbTRsdm1pejdsIn0.vcEjL7lt8OoOPMP5o1PM6g',
    showMarkers: true,
    markerColor: '#ff70ab',
    //projection: 'equirectangular',
    //Read more about available projections here
    //https://docs.mapbox.com/mapbox-gl-js/example/projections/
    inset: true,
    theme: 'light',
    use3dTerrain: false, //set true for enabling 3D maps.
    auto: false,
    title: 'Tanzifat İskeleleri',
    subtitle: 'Köpekler',
    byline: 'BAP_Mapping Metabolism of Istanbul / MEF AAP_027',
    footer: 'BAP_Mapping Metabolism of Istanbul / MEF AAP_027',
    chapters: [
        {
            id: '1',
            alignment: 'full',
            hidden: false,
            title: 'Çöp Çıkaran..! Çöp Çıkaran..!',
            image: 'https://i.ibb.co/WnWbGZ0/05-07-24-Tanzifat-skelesi-300dpi.jpg',
            description: 'The image was created for the project titled “Interactive Mapping of İstanbul’s Metabolism (MEF AAP 027)” , funded by MEF University. Project Coordinator: Dr. Esra Sert (2024–2025).',
            location: {
                center: [28.965 , 41.003],
                zoom: 12,
                pitch: 0,
                bearing: 0
            },
            mapAnimation: 'flyTo',
            rotateAnimation: false,
            callback: '',
            onChapterEnter: [
                // {
                //     layer: 'layer-name',
                //     opacity: 1,
                //     duration: 5000
                // }
            ],
            onChapterExit: [
                // {
                //     layer: 'layer-name',
                //     opacity: 0
                // }
            ]
        },
        {
            id: '2',
            alignment: 'left',
            hidden: false,
            title: 'Köpekler',
            image: 'https://i.ibb.co/zRtGzNW/image-14.jpg',
            description: 'Köpekler aslında çöp konusunda büyük bir yardımcılardı. Çöpleri yiyerek bir arıtıcı gibi çalışıyorlar ve insanlara yardımcı olurlardı. / İstanbul’da Bir Tanzifat Amelesi, 1880 / Street Cleaner In Istanbul, 1880 - Photo Source: SALT Reasearch - Abdullah Freres ',
            location: {
                center: [28.965 , 41.003],
                zoom: 12,
                pitch: 60,
                bearing: -43.2
            },
            mapAnimation: 'flyTo',
            rotateAnimation: false,
            callback: '',
            onChapterEnter: [],
            onChapterExit: []
        },
        {
            id: '3',
            alignment: 'right',
            hidden: false,
            title: '',
            image: 'https://i.ibb.co/S3M6Ts3/image-15.jpg',
            description: '“...sokaklara atılan çöpleri ortadan kaldırmak ve gece vakti gezinenlerden kötü niyetli olanlara havlayıp saldırmaktan ibarettir...” (İbrahim Şinasi, Tasvir-i Efkar, nr. 192, 5 Mayıs 1864, Sayfa 1-3.) / Köpekler Etrafındaki Tanzifat Amelesi Eşeğiyle Beraber / Street Cleaner with His Donkey and Dogs Around - Original Photo Source: Osmanlı’dan Günümüze Temizlik İşçileri ve Aletleri Sergisi, Kağıthane Belediye Başkanlığı ',
            location: {
                center: [28.978 , 41.010],
                zoom: 14,
                pitch: 30,
                bearing: 0
            },
            mapAnimation: 'flyTo',
            rotateAnimation: false,
            callback: '',
            onChapterEnter: [],
            onChapterExit: []
        },
        {
            id: '4',
            alignment: 'middle',
            hidden: false,
            title: '',
            image: 'https://i.ibb.co/Hh44hwL/image-16.jpg',
            description: 'TR: “Şunu merak ettim fakat rahat bırakmıyor!” “Korkma efendim, külhani insancıdır, siz devam ediniz!” - Photo Source: Geveze, nr: 1, 15 Ağustos 1875',
            location: {
                center: [28.978 , 41.010],
                zoom: 16,
                pitch: 0,
                bearing: 0
            },
            mapAnimation: 'flyTo',
            rotateAnimation: false,
            callback: '',
            onChapterEnter: [],
            onChapterExit: []
        },
        {
            id: '5',
            alignment: 'left',
            hidden: false,
            title: 'Hayırsızada',
            image: 'https://i.ibb.co/Lv3hf7C/1-page-0001.jpg',
            description: 'Sivriada, 1910 yılında İstanbul’daki sokak köpeklerinin sürgün edildiği yer olarak bilinir. O dönemde, şehirdeki köpek nüfusu yoğunlaşmıştı ve özellikle Batılılaşma süreciyle birlikte, Osmanlı yönetimi, sokak hayvanlarını şehirden uzaklaştırmayı amaçlar. Bu karar, halk arasında büyük tepkilere yol açsa da binlerce köpek, teknelere bindirilerek İstanbul’un gözden uzak noktalarından biri olan Sivriada’ya götürülür. - Photo Source: Yeni Geveze, nr. 33, 6 Temmuz 1910, Çizen: M. Ütücüyan',
            location: {
                center: [28.9725, 40.8759],
                zoom: 15,
                pitch: 60,
                bearing: -43.2
            },
            mapAnimation: 'flyTo',
            rotateAnimation: true,
            callback: '',
            onChapterEnter: [],
            onChapterExit: []
        },
        {
            id: '6',
            alignment: 'right',
            hidden: false,
            title: '',
            image: 'https://i.ibb.co/vvt4PnG/2-page-0001.jpg',
            description: 'Sivriada, adının da işaret ettiği gibi, kayalık ve zorlu bir araziye sahipti, yiyecek veya su kaynağı olmayan bir yerdi. Sürgüne gönderilen köpeklerin adada kendi başlarına hayatta kalmaları neredeyse imkansızdı. Ada sakinleri ise köpeklerin acı seslerine karşı gelemeyerek şikayette bulundular ve nihayet sürgüne yollanan köpekler yurtlarına geri getirildi. - Photo Source: Karikatürlerde İstanbul’un Sokak Köpekleri, Kemalettin Kuzucu, Sayfa 330.',
            location: {
                center: [28.9725, 40.8759],
                zoom: 15,
                pitch: 0,
                bearing: 0
            },
            mapAnimation: 'flyTo',
            rotateAnimation: false,
            callback: '',
            onChapterEnter: [],
            onChapterExit: []
        },
    ]
};
            id: 'harrison1998',
            alignment: 'left',
            title: 'Harrison Glacier, 1998',
            image: '',
            description: 'Harrison Glacier is located in the US state of Montana in Glacier National Park. Situated on a southeast facing ridge immediately south of Mount Jackson, Harrison Glacier is the largest glacier in Glacier National Park...',
            location: {
                center: [-113.72917, 48.58938],
                zoom: 12.92,
                pitch: 39.50,
                bearing: 36.00
            },
            onChapterEnter: [],
            onChapterExit: [
                // {
                //     layer: 'gnpglaciers-2015',
                //     opacity: 0
                // }
            ]
        }
    ]
}
```

#### Configuration Options

Note: items in bold are **required**.

**`style`**: This is the Mapbox style `url` to use for the app. It can be a standard style, or a custom style from your Mapbox account. Use a custom style if you want to include custom data or layers.

**`accessToken`**: Your Mapbox access token.

**`showMarkers`**: This controls whether markers are shown at the centerpoint of each chapter. If `true`, the map will display a default blue, inverted-teardrop icon.

**`markerColor`**: Accepts hexadecimal, RGB, and color names [compatible with CSS standards](https://developer.mozilla.org/en-US/docs/Web/CSS/color_value). If `showMarkers` is `true`, this property will override the default light blue marker color.

**`theme`**: Two basic themes (light and dark) are available.

`use3dTerrain`: Enables 3D terrain. (Optional)

`inset`: Enables inset map. (Optional)

`projection`: Set the Map object's [projection parameter](https://docs.mapbox.com/mapbox-gl-js/example/projections/) to create a map with a non-Mercator projection.. (Optional)

`auto`: Enables automatic advancement through the chapters. (Optional)

`title`: The title of the overall story. (Optional)

`subtitle`: A subtitle for the story. (Optional)

`byline`: Credit the author of the story. (Optional)

`footer`: Citations, credits, etc. that will be displayed at the bottom of the story.

**`chapters`**: This contains all of the story content and map controls for each section of the story. _Array of objects_

- **`id`**: A slug-style ID for the chapter. This is read by the JavaScript driving the app and is assigned as an HTML `id` for the `div` element containing the rest of the story. A best-practice format would be to use kebab case, like `my-story-chapter-1`.
- **`alignment`**: This defines where the story text should appear over the map. Options are `center`, `left`, `right`, and `full`. When the browser window is less than 750 pixels wide, the story will be `center` aligned.
- `hidden`: Sets the visibility of the chapter to `hidden` when `true`. The chapter will still trigger a map and layer transition.
- `title`: The title of the section, displayed in an `h3` element.
- `image`: The path to an image to display in this section.
- `description`: The main story content for the section. This should be aligned with what the reader is seeing on the map. In the vanilla version, this field will render as HTML. Images, links, and other items can be included as HTML.
- **`location`**: Details about the map display and camera view.
    - **`center`**: Center coordinates of the map, as `longitude, latitude`
    - **`zoom`**: Zoom level of the map.
    - **`pitch`**: Angle of the map view. `0` is straight down, and `60` is highly tilted.
    - **`bearing`**: Degrees of rotation clockwise from North (`0`). Negative values represent counter-clockwise rotation.
- `mapAnimation`: Defines the [animation type](https://docs.mapbox.com/mapbox-gl-js/api/#map#jumpto) for transitioning between locations. This property supports 'flyTo', 'easeTo', and 'jumpTo' animations. If not specified, defaults to `flyTo`.
    - flyTo and easeTo [options](https://docs.mapbox.com/mapbox-gl-js/api/map/#flyto-parameters) (`curve`, `maxDuration`, `minZoom`, `screenSpeed`, `speed`) can be included in the `location` array, for example:
```
            location: {
                center: [-113.72917, 48.58938],
                zoom: 12.92,
                pitch: 39.50,
                bearing: 36.00,
                speed: 0.2,
                curve: 1
            }
```
- `rotateAnimation`: Starts a slow rotation animation at the end of the map transition when set to `true`. The map will rotate 90 degrees over 24 seconds.
- `callback`: Accepts the name of a JavaScript function and executes the function. Use this if you have custom code you want to run for a chapter, like turning a legend on or off, adding data from an API request, or displaying an interactive graph.
- `onChapterEnter`: Layers to be displayed/hidden/muted when the section becomes active. _Array of objects_
    - `layer`: Layer name as assigned in Mapbox Studio.
    - `opacity`: The opacity to display the layer. `0` is fully transparent, `1` is fully opaque.
    - `duration`: The length of the opacity transition, numeric, in milliseconds. Default is 300. This is an optional parameter and can be omitted.
- `onChapterExit`: Same as `onChapterEnter` except it is triggered when the section becomes inactive. _Array of objects_


#### Layer Configuration in your Mapbox Studio Style

Add and style each custom layer in your Studio style. Before the final publish, set any layers's style to be hidden with `0` opacity. **Do not hide the layer**. For example, if you have a `circle` layer, makes sure the `color-opacity` and/or the `stroke-opacity` is set to 0.

This will ensure that the map appears correctly when the story page loads. To adjust the opacity of the layers as the reader scrolls through the story, use the `onChapterEnter` or `onChapterExit` configuration options to set your desired opacity for the layer.

## Deployment

Host the `index.html` and `config.js` files in the same directory in a web-accessible location. If you don't know where to start, look into GitHub Pages or Netlify.

## Built With

- Mapbox GL JS
- Scrollama.js

## Authors

John Branigan on the Mapbox [Solutions Architecture Team](mailto:solutions_architecture@mapbox.com)

## License

BSD 3-Clause License

## Acknowledgments

* Lo Bénichou for the idea, support, and awesome feedback throughout the design and build process
* Paige Moody and Lem Thornton for early testing and feedback
* Chris Toomey for ushering this work through and keeping things on track
* Journalists with stories that help us make sense of what goes around us
* [Digital Democracy](https://www.digital-democracy.org/) and [Rudo Kemper](https://kunukumapping.com/) for [their fork](https://github.com/digidem/mapbox-storytelling-upgraded) that inspired many later features.
* [Paul Franz](https://github.com/pkfranz) for developing customizations and providing feedback.

## Notable Examples

- [Connectivity Disparity Across Schools in Kazakhstan: UNICEF](https://unicef.github.io/mapbox_analysis/story/map)
- [Saving the Nile: Aljazeera](https://interactive.aljazeera.com/aje/2020/saving-the-nile/index.html)
- [49 Mile Map: San Francisco Chronicle](https://projects.sfchronicle.com/total-sf/49-mile-map/)
- [Dark Vessel Detection: ICEYE](https://www.iceye.com/use-cases/security/dark-vessel-detection/interactive-demo)
- [Nuestro Territorio Es Nuestra Vida: Digital Democracy](http://lab.digital-democracy.org/mapa-sinangoe/)
- [The Chinese Economic Footprint In Central And Eastern Europe: CSD](https://chinacapture.csd.bg/)
- [Safe passages: Washington Post](https://www.washingtonpost.com/graphics/2020/climate-solutions/wyoming-wildlife-corridor/)
- [Polar Star Inn and Seipel Hut: Huttrip](https://map.huttrip.com/ )
- [Ten Conflicts to watch in 2022: Crisis Group](https://conflicts2022.crisisgroup.org/ )
- [The Guiana Shield: The Amazon Conservation Team](https://www.amazonteam.org/maps/guiana-shield/)
- [Watchlist 2021: International Rescue Committee](https://theirc.github.io/watchlist2021/)
- [A River Drained: Kontinentalist](https://cdn-images.kontinentalist.com/static-html/food-security-mekong-river-hydropower-dam-climate-change/index.html)
- [Climate Gentrification and its impact on New York City: Judy Huynh](https://www.climategentrification.info/)

[mapbox.com/resources#solutions](https://www.mapbox.com/resources#solutions)
