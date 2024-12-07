<html>
  <head>
    <link rel="preconnect" href="https://fonts.gstatic.com/" crossorigin="" />
    <link
      rel="stylesheet"
      as="style"
      onload="this.rel='stylesheet'"
      href="https://fonts.googleapis.com/css2?display=swap&amp;family=Noto+Sans%3Awght%40400%3B500%3B700%3B900&amp;family=Plus+Jakarta+Sans%3Awght%40400%3B500%3B700%3B800"
    />

    <title>Galileo Design</title>
    <link rel="icon" type="image/x-icon" href="data:image/x-icon;base64," />

    <script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
  </head>
  <body>
    <div
      class="relative flex size-full min-h-screen flex-col bg-slate-50 justify-between group/design-root overflow-x-hidden"
      style='font-family: "Plus Jakarta Sans", "Noto Sans", sans-serif;'
    >
      <div>
        <div class="flex items-center bg-slate-50 p-4 pb-2 justify-between">
          <h2 class="text-[#0e141b] text-lg font-bold leading-tight tracking-[-0.015em] flex-1 text-center pl-12">Reservar sala</h2>
          <div class="flex w-12 items-center justify-end">
            <button
              class="flex max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-full h-12 bg-transparent text-[#0e141b] gap-2 text-base font-bold leading-normal tracking-[0.015em] min-w-0 p-0"
            >
              <div class="text-[#0e141b]" data-icon="Calendar" data-size="24px" data-weight="regular">
                <svg xmlns="http://www.w3.org/2000/svg" width="24px" height="24px" fill="currentColor" viewBox="0 0 256 256">
                  <path
                    d="M208,32H184V24a8,8,0,0,0-16,0v8H88V24a8,8,0,0,0-16,0v8H48A16,16,0,0,0,32,48V208a16,16,0,0,0,16,16H208a16,16,0,0,0,16-16V48A16,16,0,0,0,208,32ZM72,48v8a8,8,0,0,0,16,0V48h80v8a8,8,0,0,0,16,0V48h24V80H48V48ZM208,208H48V96H208V208Zm-96-88v64a8,8,0,0,1-16,0V132.94l-4.42,2.22a8,8,0,0,1-7.16-14.32l16-8A8,8,0,0,1,112,120Zm59.16,30.45L152,176h16a8,8,0,0,1,0,16H136a8,8,0,0,1-6.4-12.8l28.78-38.37A8,8,0,1,0,145.07,132a8,8,0,1,1-13.85-8A24,24,0,0,1,176,136,23.76,23.76,0,0,1,171.16,150.45Z"
                  ></path>
                </svg>
              </div>
            </button>
          </div>
        </div>
        <h3 class="text-[#0e141b] text-lg font-bold leading-tight tracking-[-0.015em] px-4 pb-2 pt-4">Calendario</h3>
        <div class="flex flex-wrap items-center justify-center gap-6 p-4">
          <div class="flex min-w-72 max-w-[336px] flex-1 flex-col gap-0.5">
            <div class="flex items-center p-1 justify-between">
              <button>
                <div class="text-[#0e141b] flex size-10 items-center justify-center" data-icon="CaretLeft" data-size="18px" data-weight="regular">
                  <svg xmlns="http://www.w3.org/2000/svg" width="18px" height="18px" fill="currentColor" viewBox="0 0 256 256">
                    <path d="M165.66,202.34a8,8,0,0,1-11.32,11.32l-80-80a8,8,0,0,1,0-11.32l80-80a8,8,0,0,1,11.32,11.32L91.31,128Z"></path>
                  </svg>
                </div>
              </button>
              <p class="text-[#0e141b] text-base font-bold leading-tight flex-1 text-center">October 2023</p>
              <button>
                <div class="text-[#0e141b] flex size-10 items-center justify-center" data-icon="CaretRight" data-size="18px" data-weight="regular">
                  <svg xmlns="http://www.w3.org/2000/svg" width="18px" height="18px" fill="currentColor" viewBox="0 0 256 256">
                    <path d="M181.66,133.66l-80,80a8,8,0,0,1-11.32-11.32L164.69,128,90.34,53.66a8,8,0,0,1,11.32-11.32l80,80A8,8,0,0,1,181.66,133.66Z"></path>
                  </svg>
                </div>
              </button>
            </div>
            <div class="grid grid-cols-7">
              <p class="text-[#0e141b] text-[13px] font-bold leading-normal tracking-[0.015em] flex h-12 w-full items-center justify-center pb-0.5">S</p>
              <p class="text-[#0e141b] text-[13px] font-bold leading-normal tracking-[0.015em] flex h-12 w-full items-center justify-center pb-0.5">M</p>
              <p class="text-[#0e141b] text-[13px] font-bold leading-normal tracking-[0.015em] flex h-12 w-full items-center justify-center pb-0.5">T</p>
              <p class="text-[#0e141b] text-[13px] font-bold leading-normal tracking-[0.015em] flex h-12 w-full items-center justify-center pb-0.5">W</p>
              <p class="text-[#0e141b] text-[13px] font-bold leading-normal tracking-[0.015em] flex h-12 w-full items-center justify-center pb-0.5">T</p>
              <p class="text-[#0e141b] text-[13px] font-bold leading-normal tracking-[0.015em] flex h-12 w-full items-center justify-center pb-0.5">F</p>
              <p class="text-[#0e141b] text-[13px] font-bold leading-normal tracking-[0.015em] flex h-12 w-full items-center justify-center pb-0.5">S</p>
              <button class="h-12 w-full text-[#0e141b] col-start-4 text-sm font-medium leading-normal">
                <div class="flex size-full items-center justify-center rounded-full">1</div>
              </button>
              <button class="h-12 w-full text-[#0e141b] text-sm font-medium leading-normal"><div class="flex size-full items-center justify-center rounded-full">2</div></button>
              <button class="h-12 w-full text-[#0e141b] text-sm font-medium leading-normal"><div class="flex size-full items-center justify-center rounded-full">3</div></button>
              <button class="h-12 w-full text-[#0e141b] text-sm font-medium leading-normal"><div class="flex size-full items-center justify-center rounded-full">4</div></button>
              <button class="h-12 w-full text-slate-50 text-sm font-medium leading-normal">
                <div class="flex size-full items-center justify-center rounded-full bg-[#1980e6]">5</div>
              </button>
              <button class="h-12 w-full text-[#0e141b] text-sm font-medium leading-normal"><div class="flex size-full items-center justify-center rounded-full">6</div></button>
              <button class="h-12 w-full text-[#0e141b] text-sm font-medium leading-normal"><div class="flex size-full items-center justify-center rounded-full">7</div></button>
              <button class="h-12 w-full text-[#0e141b] text-sm font-medium leading-normal"><div class="flex size-full items-center justify-center rounded-full">8</div></button>
              <button class="h-12 w-full text-[#0e141b] text-sm font-medium leading-normal"><div class="flex size-full items-center justify-center rounded-full">9</div></button>
              <button class="h-12 w-full text-[#0e141b] text-sm font-medium leading-normal"><div class="flex size-full items-center justify-center rounded-full">10</div></button>
              <button class="h-12 w-full text-[#0e141b] text-sm font-medium leading-normal"><div class="flex size-full items-center justify-center rounded-full">11</div></button>
              <button class="h-12 w-full text-[#0e141b] text-sm font-medium leading-normal"><div class="flex size-full items-center justify-center rounded-full">12</div></button>
              <button class="h-12 w-full text-[#0e141b] text-sm font-medium leading-normal"><div class="flex size-full items-center justify-center rounded-full">13</div></button>
              <button class="h-12 w-full text-[#0e141b] text-sm font-medium leading-normal"><div class="flex size-full items-center justify-center rounded-full">14</div></button>
              <button class="h-12 w-full text-[#0e141b] text-sm font-medium leading-normal"><div class="flex size-full items-center justify-center rounded-full">15</div></button>
              <button class="h-12 w-full text-[#0e141b] text-sm font-medium leading-normal"><div class="flex size-full items-center justify-center rounded-full">16</div></button>
              <button class="h-12 w-full text-[#0e141b] text-sm font-medium leading-normal"><div class="flex size-full items-center justify-center rounded-full">17</div></button>
              <button class="h-12 w-full text-[#0e141b] text-sm font-medium leading-normal"><div class="flex size-full items-center justify-center rounded-full">18</div></button>
              <button class="h-12 w-full text-[#0e141b] text-sm font-medium leading-normal"><div class="flex size-full items-center justify-center rounded-full">19</div></button>
              <button class="h-12 w-full text-[#0e141b] text-sm font-medium leading-normal"><div class="flex size-full items-center justify-center rounded-full">20</div></button>
              <button class="h-12 w-full text-[#0e141b] text-sm font-medium leading-normal"><div class="flex size-full items-center justify-center rounded-full">21</div></button>
              <button class="h-12 w-full text-[#0e141b] text-sm font-medium leading-normal"><div class="flex size-full items-center justify-center rounded-full">22</div></button>
              <button class="h-12 w-full text-[#0e141b] text-sm font-medium leading-normal"><div class="flex size-full items-center justify-center rounded-full">23</div></button>
              <button class="h-12 w-full text-[#0e141b] text-sm font-medium leading-normal"><div class="flex size-full items-center justify-center rounded-full">24</div></button>
              <button class="h-12 w-full text-[#0e141b] text-sm font-medium leading-normal"><div class="flex size-full items-center justify-center rounded-full">25</div></button>
              <button class="h-12 w-full text-[#0e141b] text-sm font-medium leading-normal"><div class="flex size-full items-center justify-center rounded-full">26</div></button>
              <button class="h-12 w-full text-[#0e141b] text-sm font-medium leading-normal"><div class="flex size-full items-center justify-center rounded-full">27</div></button>
              <button class="h-12 w-full text-[#0e141b] text-sm font-medium leading-normal"><div class="flex size-full items-center justify-center rounded-full">28</div></button>
              <button class="h-12 w-full text-[#0e141b] text-sm font-medium leading-normal"><div class="flex size-full items-center justify-center rounded-full">29</div></button>
              <button class="h-12 w-full text-[#0e141b] text-sm font-medium leading-normal"><div class="flex size-full items-center justify-center rounded-full">30</div></button>
            </div>
          </div>
        </div>
        <h3 class="text-[#0e141b] text-lg font-bold leading-tight tracking-[-0.015em] px-4 pb-2 pt-4">Horarios disponibles</h3>
        <div class="flex items-center gap-4 bg-slate-50 px-4 min-h-[72px] py-2 justify-between">
          <div class="flex items-center gap-4">
            <div
              class="bg-center bg-no-repeat aspect-square bg-cover rounded-lg size-14"
              style='background-image: url("https://cdn.usegalileo.ai/sdxl10/883463fe-b3f3-4e78-8fb8-a3e63953840e.png");'
            ></div>
            <div class="flex flex-col justify-center">
              <p class="text-[#0e141b] text-base font-medium leading-normal line-clamp-1">Sala 1</p>
              <p class="text-[#4e7397] text-sm font-normal leading-normal line-clamp-2">Para 2 personas</p>
            </div>
          </div>
          <div class="shrink-0">
            <button
              class="flex min-w-[84px] max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-full h-8 px-4 bg-[#e7edf3] text-[#0e141b] text-sm font-medium leading-normal w-fit"
            >
              <span class="truncate">9:00 AM</span>
            </button>
          </div>
        </div>
        <div class="flex items-center gap-4 bg-slate-50 px-4 min-h-[72px] py-2 justify-between">
          <div class="flex items-center gap-4">
            <div
              class="bg-center bg-no-repeat aspect-square bg-cover rounded-lg size-14"
              style='background-image: url("https://cdn.usegalileo.ai/sdxl10/d4a2b1a4-edbf-466a-8136-82a34809d8b0.png");'
            ></div>
            <div class="flex flex-col justify-center">
              <p class="text-[#0e141b] text-base font-medium leading-normal line-clamp-1">Sala 2</p>
              <p class="text-[#4e7397] text-sm font-normal leading-normal line-clamp-2">Para 4 personas</p>
            </div>
          </div>
          <div class="shrink-0">
            <button
              class="flex min-w-[84px] max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-full h-8 px-4 bg-[#e7edf3] text-[#0e141b] text-sm font-medium leading-normal w-fit"
            >
              <span class="truncate">9:30 AM</span>
            </button>
          </div>
        </div>
        <div class="flex items-center gap-4 bg-slate-50 px-4 min-h-[72px] py-2 justify-between">
          <div class="flex items-center gap-4">
            <div
              class="bg-center bg-no-repeat aspect-square bg-cover rounded-lg size-14"
              style='background-image: url("https://cdn.usegalileo.ai/sdxl10/14d7ab98-d153-49c1-974a-19358e0505c8.png");'
            ></div>
            <div class="flex flex-col justify-center">
              <p class="text-[#0e141b] text-base font-medium leading-normal line-clamp-1">Sala 3</p>
              <p class="text-[#4e7397] text-sm font-normal leading-normal line-clamp-2">Para 8 personas</p>
            </div>
          </div>
          <div class="shrink-0">
            <button
              class="flex min-w-[84px] max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-full h-8 px-4 bg-[#e7edf3] text-[#0e141b] text-sm font-medium leading-normal w-fit"
            >
              <span class="truncate">10:00 AM</span>
            </button>
          </div>
        </div>
      </div>
      <div>
        <div class="flex px-4 py-3">
          <button
            class="flex min-w-[84px] max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-full h-12 px-5 flex-1 bg-[#1980e6] text-slate-50 text-base font-bold leading-normal tracking-[0.015em]"
          >
            <span class="truncate">Reservar</span>
          </button>
        </div>
        <div class="h-5 bg-slate-50"></div>
      </div>
    </div>
  </body>
</html>

