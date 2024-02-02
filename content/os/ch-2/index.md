---
title: "CH ONE"
date: 2024-02-02
categories: [ "tech" ]
series: [ "Operating System" ]
series_order: 2
---
# CHAPTER ONE

## Alert

{{< alert >}}
**Warning!** This action is destructive!
{{< /alert >}}

<br>

{{< alert "twitter" >}}
Don't forget to [follow me](https://twitter.com/nunocoracao) on Twitter.
{{< /alert >}}

<br>

{{< alert icon="fire" cardColor="#e63946" iconColor="#1d3557" textColor="#f1faee" >}}
This is an error!
{{< /alert >}}


## Article

{{< article link="/posts/one/" >}}


## Badge

{{< badge >}}
New article!
{{< /badge >}}


## Button

{{< button href="#carousel" target="_self" >}}
go to "Carousel"
{{< /button >}}


## Carousel

{{< carousel images="{gallery/03.jpg, gallery/01.jpg, gallery/02.jpg, gallery/04.jpg}" >}}

*OR*

{{< carousel images="gallery/*" aspectRatio="21-9" interval="2500" >}}


## Chart

{{< chart >}}
type: 'bar',
data: {
  labels: ['Tomato', 'Blueberry', 'Banana', 'Lime', 'Orange'],
  datasets: [{
    label: '# of votes',
    data: [12, 19, 3, 5, 3],
  }]
}
{{< /chart >}}


## Gallery

{{< gallery >}}
  <img src="gallery/01.jpg" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="gallery/02.jpg" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="gallery/03.jpg" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="gallery/04.jpg" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="gallery/05.jpg" class="grid-w50 md:grid-w33 xl:grid-w25" />
{{< /gallery >}}

