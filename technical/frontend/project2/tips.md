لاخفاء عنصر  

transform : scale(0 , 0) in width , height

  

  nav > ul li  .link-item::after {

    position: absolute;

    display: block;

    padding: 2px;

    content: "";

    border-color: var(--main-color);

    border-width: 2px 0;

    border-style: solid;

    width: 96%;

    height: 94%;

    top: 0;

    right: 0;

    transform: scale3d(0, 1, 1);

    transition: transform .4s;

   transform-origin: left;

  }

  nav > ul li  .link-item:hover:after {

    transform: scale3d(1,1,1);

  }
 لو عاوز التحرك يبدا من الشمال بعمل الوريحين 
 بعمل scale3d عشان يبدا من الاطراف ببص ايه اللى عاوز اغيره ال width فى اتجاه اكس ولا الطول فى اتجاه y 