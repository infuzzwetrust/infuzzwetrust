<div style="display: flex; align-items: center; justify-content: space-between; flex-wrap: wrap; margin: 20px 0;">

  <!-- Left column: image -->
  <div style="flex: 0 0 20%; text-align: center;">
    <img src="https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExdHQ5bHJyczZ6cmozODMzNXR5c2Zndm05cTZydTI1Z3VmbGJpMDVrYSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/9GO5y3UT3upiW9gO2P/giphy.gif"
         alt="kittycat from https://giphy.com/gifs/art-pixel-animals-9GO5y3UT3upiW9gO2P"
         style="max-width: 60%; height: auto; display: block; margin: auto;">
  </div>

  <!-- Right column: headings -->
  <div style="flex: 0 0 80%; padding-left: 20px; box-sizing: border-box;">
    <h1 style="font-family: 'Bitcount Grid Double Ink', sans-serif; font-size: 60px; line-height: 1; margin: 0;">
      Welcome to InFuzzLand
    </h1>
  </div>
    <h3 style="font-family: 'Atomic Age', sans-serif; font-style: italic; margin-top: 10px;">Yet another space where cyber things get discovered and distributed.</h3>
</div>

<!-- Responsive CSS -->
<style>
  @media screen and (max-width: 768px) {
    div[style*="display: flex"] {
      flex-direction: column;   /* stack image and text */
      align-items: center;
    }
    div[style*="flex: 0 0 20%"] {
      flex: 0 0 50%;            /* image wider on small screens */
      margin-bottom: 20px;
    }
    div[style*="flex: 0 0 80%"] {
      flex: 0 0 90%;            /* text takes more width */
      padding-left: 0;          /* remove left padding */
      text-align: center;       /* center headings */
    }
    h1 {
      font-size: 40px;          /* scale down font */
    }
    h3 {
      font-size: 18px;          /* scale down subtitle */
      padding-left: 0;
    }
  }
</style>

---

List of bloggies: