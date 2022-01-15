<template>
  <div class="bg-gray-100">
    <div class="bg-white">
        <div class="container py-5 mx-auto">
          <div class="flex flex-row items-center">
            <div class="w-3/12">
              <MoladinLogo />
            </div>
            <div class="w-6/12">
              <ul class="flex flex-row font-light text-sm justify-between items-center">
                  <li><a href="#" class="focus:text-blue-500">Home</a></li>
                  <li><a href="#" class="focus:text-blue-500">Beli Mobil Bekas</a></li>
                  <li><a href="#" class="focus:text-blue-500">Jual Mobil Bekas</a></li>
                  <li><a href="#" class="focus:text-blue-500">Tentang Moladin</a></li>
                  <li><a href="#" class="focus:text-blue-500">Pusat Info Agen</a></li>
                  <li><a href="#" class="focus:text-blue-500">Blog</a></li>
              </ul>
            </div>
          </div>
        </div>
    </div>
    <div class="bg-gradient-to-b from-sky-400 to-sky-600">
      <div class="container mx-auto pt-28 pb-24 flex flex-row">
        <div class="w-7/12 space-y-3">
            <p class="text-6xl font-bold text-white tracking-wider">Platform  jual  beli  mobil  bekas  berkualitas  terbaik.</p>
            <p class="text-white text-lg">Dengan jaringan komunitas 10.000+ Agen, Moladin siap membantu Anda menemukan mobil impian.</p>
        </div>
        <div class="w-5/12">
            <img src="/hero-home.png" alt="Home">
        </div>
      </div>
    </div>
    <div class="container mx-auto pb-20">
        <div class="bg-white -mt-40 rounded-3xl p-5 flex flex-row divide-x shadow-xl shadow-gray-200/50">
            <div class="w-8/12 pr-5">
                <div class="flex flex-row justify-between items-center">
                    <span class="text-2xl font-semibold text-gray-700">Beli Mobil Bekas</span>
                    <a href="#" class="flex flex-row items-center text-sky-500">
                        <span class="text-sm">Lebih Lanjut</span>
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 7l5 5m0 0l-5 5m5-5H6" />
                        </svg>
                    </a>
                </div>
                <div class="bg-gray-100 p-3 rounded-xl space-y-3">
                    <div>
                        <div class="mt-1 relative rounded-md shadow-sm">
                          <div class="absolute inset-y-0 left-0 pl-3 flex items-center pointer-events-none">
                            <span class="text-gray-500">
                              <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-gray-400" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5.121 17.804A13.937 13.937 0 0112 16c2.5 0 4.847.655 6.879 1.804M15 10a3 3 0 11-6 0 3 3 0 016 0zm6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
                              </svg>
                            </span>
                          </div>
                          <input type="text" name="price" id="price" class="focus:ring-indigo-500 focus:border-indigo-500 block w-full pl-10 pr-12 py-4 sm:text-sm border-gray-300 rounded-md" placeholder="Nama Anda">  
                        </div>
                    </div>
                    <div>
                        <input class="border w-full text-sm py-4 px-3 rounded-lg" type="text" name="merk" placeholder="Model">
                    </div>
                    <div class="flex flex-row space-x-4">
                        <input class="border w-full text-sm py-4 px-3 rounded-lg" type="text" name="merk" placeholder="Tahun">
                        <input class="border w-full text-sm py-4 px-3 rounded-lg" type="text" name="merk" placeholder="Cari Lokasi">
                    </div>
                    <div>
                        <input class="border w-full text-sm py-4 px-3 rounded-lg" type="text" name="merk" placeholder="Nama Anda">
                    </div>
                    <div>
                        <input class="border w-full text-sm py-4 px-3 rounded-lg" type="text" name="merk" placeholder="Nomor Handphone">
                    </div>
                    <div>
                        <div class="mt-1 relative rounded-md shadow-sm">
                          <div class="absolute inset-y-0 left-0 pl-3 flex items-center pointer-events-none">
                            <span class="text-gray-500">
                              
                            </span>
                          </div>
                          <input type="text" name="price" id="price" class="focus:ring-indigo-500 focus:border-indigo-500 block w-full pl-7 pr-12 py-4 sm:text-sm border-gray-300 rounded-md" placeholder="0.00">  
                        </div>
                    </div>
                    <button class="w-full bg-amber-400 py-4 rounded-xl font-semibold">
                        Tanyakan
                    </button>
                </div>
            </div>
            <div class="w-4/12 pl-5">
                <div class="flex flex-row justify-between items-center">
                    <span class="text-2xl font-semibold text-gray-700">Jual Mobil Bekas</span>
                    <a href="#" class="flex flex-row items-center text-sky-500">
                        <span class="text-sm">Lebih Lanjut</span>
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 7l5 5m0 0l-5 5m5-5H6" />
                        </svg>
                    </a>
                </div>
                <div class="bg-gray-100 p-3 rounded-xl space-y-3">
                    <div>
                        <input class="border w-full text-sm py-4 px-3 rounded-lg" type="text" name="merk" placeholder="Merk">
                    </div>
                    <div>
                        <input class="border w-full text-sm py-4 px-3 rounded-lg" type="text" name="merk" placeholder="Model">
                    </div>
                    <div class="flex flex-row space-x-4">
                        <input class="border w-full text-sm py-4 px-3 rounded-lg" type="text" name="merk" placeholder="Tahun">
                        <input class="border w-full text-sm py-4 px-3 rounded-lg" type="text" name="merk" placeholder="Cari Lokasi">
                    </div>
                    <div>
                        <div class="mt-1 relative rounded-md shadow-sm">
                          <div class="absolute inset-y-0 left-0 pl-3 flex items-center pointer-events-none">
                            <span class="text-gray-500">
                              <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-gray-400" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5.121 17.804A13.937 13.937 0 0112 16c2.5 0 4.847.655 6.879 1.804M15 10a3 3 0 11-6 0 3 3 0 016 0zm6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
                              </svg>
                            </span>
                          </div>
                          <input type="text" name="price" id="price" class="focus:ring-indigo-500 focus:border-indigo-500 block w-full pl-10 pr-12 py-4 sm:text-sm border-gray-300 rounded-md" placeholder="Nama Anda">  
                        </div>
                    </div>
                    <div>
                        <div class="mt-1 relative rounded-md shadow-sm">
                          <div class="absolute inset-y-0 left-0 pl-3 flex items-center pointer-events-none">
                            <span class="text-gray-400 text-sm">
                              +62
                            </span>
                          </div>
                          <input type="text" name="price" id="price" class="focus:ring-indigo-500 focus:border-indigo-500 block w-full pl-12 pr-12 py-4 sm:text-sm border-gray-300 rounded-md" placeholder="Nama Anda">  
                        </div>
                    </div>
                    <button class="w-full bg-amber-400 py-4 rounded-xl font-semibold">
                        Tanyakan
                    </button>
                </div>
            </div>
        </div>
        <div class="container mx-auto text-3xl font-bold text-center space-y-4 text-gray-700 mt-20">
            <p>Apa saja keuntungan yang Anda dapatkan</p>
            <p>dengan menggunakan Moladin?</p>
        </div>

        <div class="flex flex-row space-x-5 mt-28">
            <div class="w-3/12 bg-white rounded-3xl flex flex-col items-center space-y-4 px-2 pb-10">
                <div class="bg-sky-100 w-20 h-20 flex items-center justify-center rounded-3xl -mt-10">
                    <img src="/benefit-best-ucr.png" alt="car">
                </div>
                <div class="text-xl text-gray-700 text-center font-bold">Beli Mobil Bekas Terbaik</div>
                <div class="text-sm font-light text-gray-500 text-center ">Dengan tim berpengalaman yang melakukan inspeksi mobil secara rutin untuk menjamin kualitasnya.</div>
            </div>
            <div class="w-3/12 bg-white rounded-3xl flex flex-col items-center space-y-4 px-2 pb-10">
                <div class="bg-sky-100 w-20 h-20 flex items-center justify-center rounded-3xl -mt-10">
                    <MoladinCar />
                </div>
                <div class="text-xl text-gray-700 text-center font-bold">Jual Mobil Bekas Cepat</div>
                <div class="text-sm font-light text-gray-500 text-center">Mobil yang anda jual akan terdaftar di platform jual beli yang dapat di akses oleh semua Agen Moladin</div>
            </div>
            <div class="w-3/12 bg-white rounded-3xl flex flex-col items-center space-y-4 px-2 pb-10">
                <div class="bg-sky-100 w-20 h-20 flex items-center justify-center rounded-3xl -mt-10">
                    <MoladinRibbon />
                </div>
                <div class="text-xl text-gray-700 text-center font-bold">Nikmati Kemudahan</div>
                <div class="text-sm font-light text-gray-500 text-center">Transaksi sangat mudah dan aman karena di dampingi oleh tim Moladin yang selalu siap membantu</div>
            </div>
            <div class="w-3/12 bg-white rounded-3xl flex flex-col items-center space-y-4 px-2 pb-10">
                <div class="bg-sky-100 w-20 h-20 flex items-center justify-center rounded-3xl -mt-10">
                    <MoladinCoinCycle />
                </div>
                <div class="text-xl text-gray-700 text-center font-bold">Dapat Uang Tambahan</div>
                <div class="text-sm font-light text-gray-500 text-center">Melalui jaringan Agen dan Mitra keuangan yang lebih luas sehingga penjualanmu jadi lebih mudah</div>
            </div>
        </div>
    </div>

    <div class="bg-sky-50 py-10">
        <div class="container mx-auto">
            <div class="flex flex-row justify-between items-center">
                <span class="text-2xl font-semibold text-gray-700">Rekomendasi Mobil</span>
                <a href="#" class="flex flex-row items-center text-sky-500 underline underline-offset-8">
                    <span class="">Lihat Semua Mobil</span>
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 7l5 5m0 0l-5 5m5-5H6" />
                    </svg>
                </a>
            </div>
        </div>
    </div>
  </div>
</template>
