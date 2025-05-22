# Ex09 Event Registration Web Application
## Date:22/5/2025

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```

Home page
<div
  class="flex flex-col items-center pt-4 pb-2 mx-auto w-full text-sm font-black text-black bg-white max-w-[480px]"
>
  <div
    class="flex gap-5 justify-between w-full text-base font-semibold tracking-tight text-center whitespace-nowrap max-w-[328px]"
  >
    <div class="my-auto">9:27</div>
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/TEMP/d6f0203923fac640f43c1305992ca634564a25dabde5b255fe95aa3d60dd894d?"
      class="shrink-0 aspect-[4.17] w-[68px]"
    />
  </div>
  <img
    loading="lazy"
    srcset="..."
    class="self-stretch mt-5 w-full aspect-[6.67]"
  />
  <img
    loading="lazy"
    srcset="..."
    class="mt-16 max-w-full aspect-[1.03] w-[167px]"
  />
  <div class="mt-7 font-bold text-blue-600">SPORTS DAY EVENTS</div>
  <div
    class="justify-center items-center px-16 py-6 mt-10 max-w-full tracking-wide text-center uppercase bg-red-600 rounded-md border-2 border-black border-solid w-[167px]"
  >
    log in
  </div>
  <div
    class="justify-center px-14 py-6 mt-6 max-w-full tracking-wide text-center uppercase whitespace-nowrap bg-red-600 rounded-md border-2 border-black border-solid w-[167px]"
  >
    REGISTER
  </div>
  <img
    loading="lazy"
    srcset="..."
    class="self-stretch mt-9 w-full aspect-[1.72]"
  />
  <div class="shrink-0 mt-4 bg-black rounded-xl h-[5px] w-[135px]"></div>
</div>
Events Page
<div class="flex flex-col mx-auto w-full bg-white max-w-[480px]">
  <div class="flex z-10 gap-0 w-full text-base">
    <div class="flex flex-col py-16 pl-4 text-blue-600 bg-white">
      <img
        loading="lazy"
        src="https://cdn.builder.io/api/v1/image/assets/TEMP/31f970f8c0a58e640266f61d2f01c7fbd583cce431a7bd18b2cfa725bc5c34c9?"
        class="w-3 aspect-[1.09] fill-black fill-opacity-80"
      />
      <div class="self-start mt-2 text-4xl tracking-tight text-red-600">
        SPORTS DAY EVENT
     
      <img
        loading="lazy"
        src="https://cdn.builder.io/api/v1/image/assets/TEMP/d6f0203923fac640f43c1305992ca634564a25dabde5b255fe95aa3d60dd894d?"
        class="shrink-0 aspect-[4.17] w-[68px]"
      />
    </div>
        <div class="justify-center px-3.5 py-3 bg-white rounded-md shadow-sm">
          j
        </div>
        <div class="items-start px-3 pt-2.5 pb-4 bg-white rounded-md shadow-sm">
          k
        </div>
        <div class="items-start px-4 pt-2.5 pb-4 bg-white rounded-md shadow-sm">
          l
        </div>
      </div>
        </div>
        <div class="justify-center px-6 py-4 bg-gray-400 rounded-md shadow-sm">
          return
        </div>
      </div>
      <div class="flex relative gap-5 justify-between items-start mx-7 mt-6">
        <img
          loading="lazy"
          src="https://cdn.builder.io/api/v1/image/assets/TEMP/4bdb32381f99df16e1860ee172953e977185ff0971e58b512ae6d8a821552eca?"
          class="shrink-0 aspect-square w-[26px]"
        />
        <img
          loading="lazy"
          src="https://cdn.builder.io/api/v1/image/assets/TEMP/0251bdf8580d344097fea5efa65f3c279517c4b694e19f5e240f8900f62d532b?"
          class="shrink-0 aspect-[0.6] w-[15px]"
        />
      </div>
    </div>
    <div
      class="shrink-0 self-center bg-black rounded-xl h-[5px] w-[135px]"
    ></div>
  </div>
</div>
Event Registration form
<div
  class="flex flex-col justify-center mx-auto w-full text-sm font-black tracking-wide text-black bg-white max-w-[480px]"
>
  <div class="flex flex-col pt-4 w-full bg-white">
    <div class="flex flex-col px-4 w-full">
      <div
        class="flex gap-5 justify-end self-start ml-4 text-base font-semibold tracking-tight text-center whitespace-nowrap"
      >
        <div class="my-auto">9:27</div>
        <img
          loading="lazy"
          src="https://cdn.builder.io/api/v1/image/assets/TEMP/d6f0203923fac640f43c1305992ca634564a25dabde5b255fe95aa3d60dd894d?"
          class="shrink-0 aspect-[4.17] w-[68px]"
        />
      </div>
      <img
        loading="lazy"
        src="https://cdn.builder.io/api/v1/image/assets/TEMP/31f970f8c0a58e640266f61d2f01c7fbd583cce431a7bd18b2cfa725bc5c34c9?"
        class="mt-7 w-3 aspect-[1.09] fill-black fill-opacity-80"
      />
      <div class="mt-8 text-4xl tracking-tight text-fuchsia-900">
        EVENT REGISTRATION FORM
      </div>
      <div class="mt-14 text-center uppercase text-zinc-600">
        Fill the details
      </div>
      <div
        class="justify-center items-start px-3.5 py-3 mt-5 text-center uppercase bg-white border-2 border-black border-solid"
      >
        Full Name
      </div>
      <div
        class="justify-center items-start px-4 py-3 mt-2.5 text-center uppercase whitespace-nowrap bg-white border-2 border-black border-solid"
      >
        Gender
      </div>
      <div
        class="justify-center items-start px-3.5 py-3 mt-2.5 uppercase whitespace-nowrap bg-white border-2 border-black border-solid"
      >
        AGE
      </div>
      <div
        class="justify-center items-start px-4 py-3 mt-2.5 uppercase bg-white border-2 border-black border-solid"
      >
        REGISTER NUMBER
      </div>
      <div
        class="justify-center items-start px-3 py-3 mt-2.5 uppercase whitespace-nowrap bg-white border-2 border-black border-solid"
      >
        DEPARTMENT
      </div>
      <div
        class="justify-center items-start px-3 py-3 mt-2.5 uppercase bg-white border-2 border-black border-solid"
      >
        MOBILE NUMBER
      </div>
    </div>
    <div
      class="flex overflow-hidden relative flex-col items-start pt-2.5 pr-20 pb-20 pl-4 w-full uppercase aspect-[1.04]"
    >
      <img
        loading="lazy"
        srcset="..."
        class="object-cover absolute inset-0 size-full"
      />
      <div
        class="relative justify-center items-start px-3 py-3 max-w-full bg-white border-2 border-black border-solid w-[245px]"
      >
        EMAIL ID
      </div>
      <div
        class="relative justify-center items-start px-3 py-3 mt-2.5 max-w-full bg-white border-2 border-black border-solid w-[245px]"
      >
        EVENTS TO REGISTER
      </div>
      <div
        class="relative justify-center self-center px-14 py-6 mt-7 mb-20 text-center whitespace-nowrap bg-red-600 rounded-md border-2 border-black border-solid"
      >
        REGISTER
      </div>
    </div>
  </div>
</div>
Contact us
<div class="flex flex-col justify-center mx-auto w-full bg-white max-w-[480px]">
  <div class="flex flex-col px-5 pt-4 w-full bg-white">
    <div
      class="flex gap-5 justify-end self-end text-base font-semibold tracking-tight text-center text-black whitespace-nowrap"
    >
      <div class="my-auto">9:27</div>
      <img
        loading="lazy"
        src="https://cdn.builder.io/api/v1/image/assets/TEMP/bf726325a393d53b06ea6dc79bc40f34d9e76e5fb0eef67c62993e906fc657c2?"
        class="shrink-0 aspect-[4.17] w-[68px]"
      />
    </div>
    <img
      loading="lazy"
      srcset="..."
      class="mt-3 w-full aspect-[6.67]"
    />
    <div class="self-center mt-52 text-4xl tracking-tight text-red-600">
      THANK YOU
    </div>
    <div
      class="self-center mt-8 text-sm leading-5 text-center text-black w-[343px]"
    >
      We are all eagerly waiting
      <br />
      for your participation in
      <br />
      the sports events
    </div>
    <div
      class="flex overflow-hidden relative flex-col px-11 pt-20 pb-10 mt-48 w-full aspect-[1.84]"
    >
      <img
        loading="lazy"
        srcset="..."
        class="object-cover absolute inset-0 size-full"
      />
      <div class="relative self-center mt-4 text-base text-gray-950">
        CONTACT US
      </div>
      <div class="relative mt-3.5 text-sm leading-5 text-center text-black">
        E-mail: saveethaengineeringcollege@gmail.com
        <br />
        Phone: 6369183394
        <br />
        6369183394
      </div>
    </div>
  </div>
</div>

```


## OUTPUT:
![396782031-57902b41-297e-410f-afa3-a08b229442c5](https://github.com/user-attachments/assets/f95cbc8e-4920-431f-907d-832cc2f311a6)


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
