# Prime Video App

I have completed this project, which involved building a **Prime Video** application by applying the concepts learned so far.

### Refer to the video below:

<br/>
<div style="text-align: center;">
  <a href="https://assets.ccbp.in/frontend/content/react-js/prime-video-output.mp4" target="_blank">
    <img src="https://assets.ccbp.in/frontend/content/react-js/prime-video-lg-output-img.png" alt="Prime Video Preview" style="max-width:80%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12);">
  </a>
</div>
<br/>

### Design Files

- [Large (Size >= 992px) and Extra Large (Size >= 1200px)](https://assets.ccbp.in/frontend/content/react-js/prime-video-lg-output-img.png)

### Set Up Instructions

- Download dependencies by running `npm install`
- Start up the app using `npm start`

### Completion Instructions

The app has the following functionalities:

- **Action Movies List** and **Comedy Movies List** are displayed using **React Slick**
- The `App` is provided with `moviesList`, consisting of a list of movieItem objects with the following properties in each movieItem object:

  |     Key      | Data Type |
  | :----------: | :-------: |
  |      id      |  String   |
  | thumbnailUrl |  String   |
  |   videoUrl   |  String   |
  |  categoryId  |  String   |

- When the **next button** is clicked in any of the sliders, the next movie item's thumbnail in the corresponding moviesList is displayed
- When the **previous button** is clicked in any of the sliders, the previous movie item's thumbnail in the corresponding moviesList is displayed
- When you click on the **thumbnail**, a popup opens displaying the corresponding video using the **React player** component from `react-player`
- When the close button is clicked, the popup is closed

<div style="text-align: center;">
  <img src="https://assets.ccbp.in/frontend/content/react-js/prime-video-next-previous-buttons-img.png" alt="Movie Slider Buttons" style="max-width:100%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
</div>
<br/>

### Components Structure

<div style="text-align: center;">
  <img src="https://assets.ccbp.in/frontend/content/react-js/prime-video-compoment-structure-breakdown.png" alt="Component Structure Breakdown" style="max-width:100%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
</div>

### Implementation Files

Use these files to complete the implementation:

- `src/components/PrimeVideo/index.js`
- `src/components/PrimeVideo/index.css`
- `src/components/MoviesSlider/index.js`
- `src/components/MovieItem/index.js`
- `src/components/MovieItem/index.css`

### Quick Tips

- To build this project, take a look at the [React Slick](https://learning.ccbp.in/frontend-development/course?c_id=2f4192f7-7495-49ca-a6ce-6b74005e25f1&s_id=c1dc8b6e-864b-4417-9767-471b9e745405&t_id=416f0cab-8425-413b-9157-c7b4d4ae4467), [React Popup](https://learning.ccbp.in/frontend-development/course?c_id=2f4192f7-7495-49ca-a6ce-6b74005e25f1&s_id=b01fca1c-aa5c-4d79-b81e-0220e7649bd0&t_id=416f0cab-8425-413b-9157-c7b4d4ae4467), and [React Video Player](https://learning.ccbp.in/frontend-development/course?c_id=2f4192f7-7495-49ca-a6ce-6b74005e25f1&s_id=b6392b63-25f6-4215-be09-9f23ad91d789&t_id=416f0cab-8425-413b-9157-c7b4d4ae4467) reading materials
- To style popup content use `.popup-content` class

```jsx
<Popup
  modal
  trigger={
    //write code here
  }
  className="popup-content"
>
  //write code here
</Popup>
```

### Important Note

**The following instructions are required for the tests to pass**

- One frame of the slider should have 4 thumbnails
- The thumbnail images in the app should have alt as **thumbnail**
- The close button in the popup should have the `data-testid` as **closeButton**
- `IoMdClose` from react-icons should be used for **Close Icon** in the Popup

### Resources

#### Image URLs

- [https://assets.ccbp.in/frontend/react-js/prime-video-img.png](https://assets.ccbp.in/frontend/react-js/prime-video-img.png) alt should be **prime video**

#### Colors

<br/>
<div style="background-color: #000000; width: 150px; padding: 10px; color: white">Hex: #000000</div>
<div style="background-color: #ffffff; width: 150px; padding: 10px; color: black">Hex: #ffffff</div>
<div style="background-color: #231f20; width: 150px; padding: 10px; color: white">Hex: #231f20</div>
<br/>

#### Font-families

- Roboto
