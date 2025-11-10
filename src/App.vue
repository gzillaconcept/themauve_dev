<template>

  <!-- Include this script tag or install `@tailwindplus/elements` via npm: -->
  <!-- <script src="https://cdn.jsdelivr.net/npm/@tailwindplus/elements@1" type="module"></script> -->
  <nav
    class="fixed top-0 inset-x-0 z-50 bg-gray-800/60 backdrop-blur after:pointer-events-none after:absolute after:inset-x-0 after:bottom-0 after:h-px after:bg-white/10">
    <div class="mx-auto max-w-7xl px-2 sm:px-6 lg:px-8">
      <div class="relative flex h-16 items-center justify-between">
        <div class="absolute inset-y-0 left-0 flex items-center sm:hidden">
          <!-- Mobile menu button-->
          <button type="button" command="--toggle" commandfor="mobile-menu"
            class="relative inline-flex items-center justify-center rounded-md p-2 text-gray-400 hover:bg-white/5 hover:text-white focus:outline-2 focus:-outline-offset-1 focus:outline-indigo-500">
            <span class="absolute -inset-0.5"></span>
            <span class="sr-only">Open main menu</span>
            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" data-slot="icon"
              aria-hidden="true" class="size-6 in-aria-expanded:hidden">
              <path d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5" stroke-linecap="round" stroke-linejoin="round" />
            </svg>
            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" data-slot="icon"
              aria-hidden="true" class="size-6 not-in-aria-expanded:hidden">
              <path d="M6 18 18 6M6 6l12 12" stroke-linecap="round" stroke-linejoin="round" />
            </svg>
          </button>
        </div>
        <div class="flex flex-1 gap-5 items-center justify-center sm:items-stretch sm:justify-start">
          <div class="flex shrink-0 items-center font-bold">
            <p>THE MAUVE</p>
          </div>
          <div class="hidden sm:ml-6 sm:block">
            <div class="flex space-x-4">
              <!-- Current: "bg-gray-950/50 text-white", Default: "text-gray-300 hover:bg-white/5 hover:text-white" -->
              <a href="#"
                class="rounded-md px-3 py-2 text-sm font-medium text-gray-300 hover:bg-white/5 hover:text-white">Home</a>
              <a href="#section1"
                class="rounded-md px-3 py-2 text-sm font-medium text-gray-300 hover:bg-white/5 hover:text-white">Info</a>
              <a href="#section5"
                class="rounded-md px-3 py-2 text-sm font-medium text-gray-300 hover:bg-white/5 hover:text-white">Contract
                Us</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </nav>



  <section class="relative w-full mx-auto overflow-hidden pt-15">
    <img src="../src/assets/img1.jpg" alt="Model" class="w-full h-[400px] object-cover" /> 
    <!-- กล่องข้อความอยู่ตรงกลางภาพ -->
    <div class="absolute inset-0 flex flex-col justify-center text-white p-6 pt-20 container mx-auto">
      <h2 class="text-2xl font-semibold mb-2 lg:text-4xl xl:text-6xl">สารสกัดโปรตีนไหมซิริซิน</h2>
      <h1 class="text-base font-medium lg:text-2xl xl:text-4xl">เผยความงามจากภายในสู่ภายนอก</h1>
      <p class="text-xs leading-relaxed max-w-[250px] md:max-w-[360px] xl:text-xl xl:max-w-[1100px]">
        สารบำรุงผิวที่ซ่อนเร้นอยู่ในธรรมชาติมายาวนานกว่า 4,700 ปี ซิริซินคือโปรตีนคุณภาพสูงจากใยไหม ประกอบด้วยกรดอะมิโน
        18 ชนิด ซึ่งมีคุณสมบัติใกล้เคียงกับกรดอะมิโนที่เป็นส่วนประกอบของร่างกายมนุษย์
        ช่วยเสริมสร้างและฟื้นฟูเซลล์ผิวอย่างน่าอัศจรรย์ ช่วยสร้างเซลล์ไฟโบรบลาสต์ ซึ่งมีหน้าที่สร้างคอลลาเจนโดยตรง
        และยังช่วยยับยั้งเอนไซม์ไทโรซิเนส ซึ่งเป็นสาเหตุของการเกิดเม็ดสีผิว ช่วยปรับสภาพผิวอย่างสมบูรณ์แบบ
        มีประสิทธิภาพในการซึมซาบอย่างล้ำลึก พร้อมมอบความชุ่มชื้นอย่างยาวนานถึง 300 เท่า ช่วยให้ผิวตึงกระชับ เรียบเนียน
        นุ่ม มอบความกระจ่างใสและผิวอ่อนเยาว์อย่างเป็นธรรมชาติ
      </p>
    </div>
  </section>

  <section class="relative w-full mx-auto overflow-hidden" id="section1">
    <img src="../src/assets/img3.jpg" alt="Model" class="w-full h-full object-cover" />
    <!-- กล่องข้อความอยู่ตรงกลางภาพ -->
    <div class="absolute inset-0 flex flex-col justify-center text-gray-900 p-6 container mx-auto">
      <h1 class="text-sm font-medium md:text-base lg:text-2xl xl:text-4xl">การประยุกต์ใช้ทางการแพทย์</h1>
      <p
        class="text-[8px] leading-relaxed max-w-[250px] md:max-w-[400px] md:text-xs lg:text-base xl:text-xl xl:max-w-[1100px]">
        โปรตีนไหมซิริซินมีคุณสมบัติที่ดีหลายประการ เช่น ลดการอักเสบ ต้านจุลชีพ ดูดซับและระบายความชื้นได้ดี
        เข้ากันได้ดีกับโปรตีนในร่างกายมนุษย์และสามารถกระตุ้นการเจริญเติบโตของเซลล์
        จึงถูกนำมาประยุกต์ใช้ในด้านวิศวกรรมเนื้อเยื่อทางการแพทย์ ระบบนำส่งยา สารออกฤทธิ์ หรือเพื่อรักษาโรค
        ใช้สำหรับทาแผลเพื่อช่วยรักษาความชุ่มชื้นในแผล ส่งเสริมกระบวนการสมานแผล
        กระตุ้นการสร้างคอลลาเจนเพื่อให้แผลหายเร็วขึ้น และกำจัดแบคทีเรีย </p>
    </div>
  </section>
  <div class="relative w-full mx-auto overflow-hidden" id="section2">
    <img src="../src/assets/img2.jpg" alt="Model" class="w-full h-full object-cover" />
    <!-- กล่องข้อความอยู่ตรงกลางภาพ -->
    <div class="absolute inset-0 flex flex-col items-end justify-center p-6 text-black text-right container mx-auto">
      <h1 class="text-sm font-medium md:text-base lg:text-2xl xl:text-4xl">อาหารและสุขภาพ</h1>
      <p
        class="text-[8px] leading-relaxed max-w-[250px] md:max-w-[400px] md:text-xs lg:text-base lg:max-w-[650px] xl:text-xl xl:max-w-[1100px]">
        โปรตีนซิริซินจากไหม เมื่อนำมาใช้เป็นส่วนผสมอาหาร จะมีสารที่ควบคุมคอเลสเตอรอลในหลอดเลือด สลายแอลกอฮอล์ในร่างกาย
        ช่วยความจำ และกระตุ้นการทำงานของหัวใจ อาหารที่มีโปรตีนซิริซินเป็นส่วนประกอบ เช่น ไส้กรอก มีลักษณะนุ่มละมุน
        สีสดเหมือนเพิ่งทำใหม่ๆ ไอศกรีมจะทำให้ไม่ละลายง่ายและเนียน ส่วนเส้นก๋วยเตี๋ยวจะทำให้เหนียวนุ่ม</p>
    </div>
  </div>
  <section class="relative w-full mx-auto overflow-hidden" id="section3">
    <img src="../src/assets/img4.jpg" alt="Model" class="w-full h-full object-cover" />
    <!-- กล่องข้อความอยู่ตรงกลางภาพ -->
    <div class="absolute inset-0 flex flex-col justify-center text-gray-900 p-6 container mx-auto">
      <h1 class="text-sm font-medium md:text-base lg:text-2xl xl:text-4xl">สารสกัดผงโปรตีนไหมซิริซิน</h1>
      <p
        class="text-[8px] leading-relaxed max-w-[220px] md:max-w-[400px] md:text-xs lg:text-base lg:max-w-[650px] xl:text-xl xl:max-w-[1100px]">
        สารสกัดผงโปรตีนไหมซิริซินได้จากรังไหมสีทองธรรมชาติ ใช้สำหรับเป็นส่วนผสมสำหรับการผลิตเครื่องสำอาง
        ผลิตภัณฑ์ดูแลผิว ผลิตภัณฑ์ทางการแพทย์ ทรีทเมนต์โดยตรง และสปา ฯลฯ

        ผลิตภัณฑ์สารสกัดโปรตีนไหมซิริซินของเรา ไม่ได้สกัดจากน้ำรังไหมต้มในอุตสาหกรรมทอผ้า
        กระบวนการผลิตของเราเป็นการสกัดแบบธรรมชาติด้วยการต้มรังไหมและสเปรย์ดรายให้เป็นผงปราศจากสารเคมี ไม่เป็นอันตราย
        ไม่มีส่วนผสมอื่นๆ ความเข้มข้นสูง และบริสุทธิ์ 100% เราเปิดรังไหมและนำดักแด้ออก
        เพื่อให้ดักแด้ไหมกลายเป็นผีเสื้อตามวงจรชีวิตของแมลง </p>
    </div>
  </section>
  <section class="flex flex-col items-center p-5 container mx-auto" id="section4">
    <h2 class="text-sm font-medium md:text-base lg:text-2xl xl:text-4xl">เราคือใคร</h2>
    <p
      class="text-[8px] text-center max-w-[600px] md:text-xs lg:text-base lg:max-w-[850px] xl:text-xl xl:max-w-[1100px]">
      เรามุ่งมั่นที่จะจัดหาวัตถุดิบจากธรรมชาติสำหรับบริการความงาม คัดสรรวัตถุดิบคุณภาพในราคาที่เหมาะสม
      สร้างความพึงพอใจให้กับลูกค้า และมุ่งมั่นพัฒนางานวิจัยอย่างต่อเนื่อง เรามีฟาร์มไหมขนาดเล็กเป็นของตัวเอง
      ดำเนินการมากว่า 30 ปี กระบวนการผลิตด้วยมือทุกขั้นตอน การสกัดโปรตีนไหม
      เราได้ส่งวัตถุดิบไปยังห้องปฏิบัติการและโรงงานที่ได้มาตรฐานสากล
      เราดูแลแหล่งเพาะเลี้ยงดักแด้เพื่อให้ความอบอุ่น และเพื่อให้มันเติบโตเป็นผีเสื้อตามวงจรชีวิตของแมลง</p>
  </section>

  <div class="isolate bg-gray-900 px-10 py-5" id="section5">
    <div class="mx-auto max-w-2xl text-center">
      <h2 class="text-sm font-medium p-2 md:text-base lg:text-2xl xl:text-4xl">ติดต่อเรา</h2>
      <h1 class="text-sm font-medium p-2 md:text-base lg:text-2xl xl:text-4xl">The Mauve</h1>
      <p class="text-[8px] text-center md:text-xs lg:text-base xl:text-xl">1 หมู่ 7 ต.หนองแดง อ.แม่จริม จ.น่าน 55170 เบอร์ติดต่อ : 093-4299624</p>
    </div>
    <form action="#" method="POST" class="mx-auto mt-5 max-w-xl ">
      <div class="grid grid-cols-1 gap-x-8 gap-y-6 sm:grid-cols-2">
        <div> <label for="first-name" class="block text-sm/6 font-semibold text-white">ชื่อ</label>
          <div class="mt-2.5"> <input id="first-name" type="text" name="first-name" autocomplete="given-name"
              class="block w-full rounded-md bg-white/5 px-3.5 py-2 text-base text-white outline-1 -outline-offset-1 outline-white/10 placeholder:text-gray-500 focus:outline-2 focus:-outline-offset-2 focus:outline-indigo-500" />
          </div>
        </div>
        <div> <label for="last-name" class="block text-sm/6 font-semibold text-white">นามสกุล</label>
          <div class="mt-2.5"> <input id="last-name" type="text" name="last-name" autocomplete="family-name"
              class="block w-full rounded-md bg-white/5 px-3.5 py-2 text-base text-white outline-1 -outline-offset-1 outline-white/10 placeholder:text-gray-500 focus:outline-2 focus:-outline-offset-2 focus:outline-indigo-500" />
          </div>
        </div>
        <div class="sm:col-span-2"> <label for="email" class="block text-sm/6 font-semibold text-white">อีเมล</label>
          <div class="mt-2.5"> <input id="email" type="email" name="email" autocomplete="email"
              class="block w-full rounded-md bg-white/5 px-3.5 py-2 text-base text-white outline-1 -outline-offset-1 outline-white/10 placeholder:text-gray-500 focus:outline-2 focus:-outline-offset-2 focus:outline-indigo-500" />
          </div>
        </div>
        <div class="sm:col-span-2"> <label for="message"
            class="block text-sm/6 font-semibold text-white">ข้อความ</label>
          <div class="mt-2.5"> <textarea id="message" name="message" rows="4"
              class="block w-full rounded-md bg-white/5 px-3.5 py-2 text-base text-white outline-1 -outline-offset-1 outline-white/10 placeholder:text-gray-500 focus:outline-2 focus:-outline-offset-2 focus:outline-indigo-500"></textarea>
          </div>
        </div>
      </div>
      <div class="mt-2 py-5"> <button type="submit"
          class="block w-full rounded-md bg-indigo-500 px-3.5 py-2.5 text-center text-sm font-semibold text-white shadow-xs hover:bg-indigo-400 focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-500">ส่งข้อความ</button>
      </div>
    </form>
  </div>

  <footer class="footer bg-gray-600 sm:footer-horizontal text-neutral-content justify-center items-center p-4">
    <aside class="flex">
      <p>Copyright © 2025 The Mauve - All right reserved</p>
    </aside>

  </footer>


</template>
