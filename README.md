# react-slick-slider

### Installation

### npm
```
npm install react-slick --save
```
### yarn
```
yarn add react-slick
```

### Also install slick-carousel for css and font
```
npm install slick-carousel
```
### Import Css 
``` 
// Import css files
import "slick-carousel/slick/slick.css";
import "slick-carousel/slick/slick-theme.css";
```

### or add cdn link in your html

``` 
<link
  rel="stylesheet"
  type="text/css"
  charset="UTF-8"
  href="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.6.0/slick.min.css"
/>
<link
  rel="stylesheet"
  type="text/css"
  href="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.6.0/slick-theme.min.css"
/>
```

## Example

```
import React from "react";
import Slider from "react-slick";

export default function SimpleSlider() {
  var settings = {
    dots: true,
    infinite: true,
    speed: 500,
    slidesToShow: 1,
    slidesToScroll: 1
  };
  return (


    <div className="container">
      <h1 className="h1 p-5 text-center" style={{ color: "#2C184B", textTransform: 'uppercase' }}><span style={{ color: "#BF2E6A" }}>H</span>appy <span style={{ color: "#BF2E6A" }}>E</span>mployees </h1>

      <Slider {...settings}>
        <div className="container">
          <div className="container">
            <div className="col-12 col-sm-12 col-md-10 col-lg-10 col-xl-10 offset-md-1">
              <div className="box">
                <div className="slick-testimonial slick-initialized slick-slider slick-dotted">
                  <div className="slick-list draggable">
                    <div className="slick-track" >

                      <div className="slick-slide" data-slick-index="0" aria-hidden="true" role="tabpanel"
                        id="slick-slide00" style={{ width: "920px" }}
                        aria-describedby="slick-slide-control00" tabindex="-1">
                        <div>
                          <div className="slick-item" style={{ width: "100%", display: "inlineBlock" }}>
                            <div className="row">
                              <div className="col-12 col-sm-12 col-md-4 col-lg-4 col-xl-4 offset-md-1">
                                <img style={{ height:"270px", width:"400px" }} className="img-fluid mx-auto"
                                  src="https://theadultman.com/wp-content/uploads/2022/12/Traits-of-a-High-Value-Man-Attractive-Man-in-Suit-Looking-to-the-Distance.jpg"
                                  alt="" />
                              </div>
                              <div className="col-12 col-sm-12 col-md-6 col-lg-6 col-xl-6">
                                <span className="h2 p-t-50">Zameer Ali </span>
                                <span className="h4">Laravel Developer </span>
                                <p className="p-t-30">Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda dolorum, blanditiis ducimus vitae sit ea fuga possimus. Repellat, officia ut? Velit, cupiditate impedit nam dicta perferendis voluptatum voluptatibus nemo architecto!

                                  Lorem ipsum dolor sit amet consectetur adipisicing elit. Vero odit, quas fugiat voluptas animi ex porro aliquid, cupiditate sunt natus labore possimus laboriosam nemo molestias. Minima nesciunt animi aliquid debitis?</p>
                              </div>
                            </div>
                          </div>
                        </div>
                      </div>

                    </div>
                  </div>

                </div>
              </div>
            </div>
          </div>
        </div>

        <div className="container">
          <div className="container">
            <div className="col-12 col-sm-12 col-md-10 col-lg-10 col-xl-10 offset-md-1">
              <div className="box">
                <div className="slick-testimonial slick-initialized slick-slider slick-dotted">
                  <div className="slick-list draggable">
                    <div className="slick-track" >

                      <div className="slick-slide" data-slick-index="0" aria-hidden="true" role="tabpanel"
                        id="slick-slide00" style={{ width: "920px" }}
                        aria-describedby="slick-slide-control00" tabindex="-1">
                        <div>
                          <div className="slick-item" style={{ width: "100%", display: "inlineBlock" }}>
                            <div className="row">
                              <div className="col-12 col-sm-12 col-md-4 col-lg-4 col-xl-4 offset-md-1">
                                <img style={{ height:"270px", width:"400px" }} className="img-fluid mx-auto"
                                  src="https://theadultman.com/wp-content/uploads/2022/12/Traits-of-a-High-Value-Man-Attractive-Man-in-Suit-Looking-to-the-Distance.jpg"
                                  alt=" SIDDIQUI" />
                              </div>
                              <div className="col-12 col-sm-12 col-md-6 col-lg-6 col-xl-6">
                                <span className="h2 p-t-50">Rehamn </span>
                                <span className="h4">MERN Stack Developer</span>
                                <p className="p-t-30">Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda dolorum, blanditiis ducimus vitae sit ea fuga possimus. Repellat, officia ut? Velit, cupiditate impedit nam dicta perferendis voluptatum voluptatibus nemo architecto!

                                  Lorem ipsum dolor sit amet consectetur adipisicing elit. Vero odit, quas fugiat voluptas animi ex porro aliquid, cupiditate sunt natus labore possimus laboriosam nemo molestias. Minima nesciunt animi aliquid debitis?</p>
                              </div>
                            </div>
                          </div>
                        </div>
                      </div>

                    </div>
                  </div>

                </div>
              </div>
            </div>
          </div>
        </div>

        <div className="container">
          <div className="container">
            <div className="col-12 col-sm-12 col-md-10 col-lg-10 col-xl-10 offset-md-1">
              <div className="box">
                <div className="slick-testimonial slick-initialized slick-slider slick-dotted">
                  <div className="slick-list draggable">
                    <div className="slick-track" >

                      <div className="slick-slide" data-slick-index="0" aria-hidden="true" role="tabpanel"
                        id="slick-slide00" style={{ width: "920px" }}
                        aria-describedby="slick-slide-control00" tabindex="-1">
                        <div>
                          <div className="slick-item" style={{ width: "100%", display: "inlineBlock" }}>
                            <div className="row">
                              <div className="col-12 col-sm-12 col-md-4 col-lg-4 col-xl-4 offset-md-1">
                                <img style={{ height:"270px", width:"400px" }} className="img-fluid mx-auto"
                                  src="https://theadultman.com/wp-content/uploads/2022/12/Traits-of-a-High-Value-Man-Attractive-Man-in-Suit-Looking-to-the-Distance.jpg"
                                  alt="TOOBA SIDDIQUI" />
                              </div>
                              <div className="col-12 col-sm-12 col-md-6 col-lg-6 col-xl-6">
                                <span className="h2 p-t-50">Sajjad Ali </span>
                                <span className="h4">Full Stack Developer</span>
                                <p className="p-t-30">Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda dolorum, blanditiis ducimus vitae sit ea fuga possimus. Repellat, officia ut? Velit, cupiditate      impedit nam dicta perferendis voluptatum voluptatibus nemo architecto!

                                  Lorem ipsum dolor sit amet consectetur adipisicing elit. Vero odit, quas fugiat voluptas animi ex porro aliquid, cupiditate sunt natus labore possimus laboriosam nemo molestias. Minima nesciunt animi aliquid debitis?</p>
                              </div>
                            </div>
                          </div>
                        </div>
                      </div>

                    </div>
                  </div>

                </div>
              </div>
            </div>
          </div>
        </div>

      </Slider>
    </div>

  );
}

```

## Development

```
Want to run demos locally
```

### Clone Project

```
git clone https://github.com/akiran/react-slick
cd react-slick
npm install
npm start
open http://localhost:3000

```



