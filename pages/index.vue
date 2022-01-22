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
            <div class="w-8/12 pr-5 space-y-5">
                <div class="flex flex-row justify-between items-center">
                    <span class="text-2xl font-semibold text-gray-700">Beli Mobil Bekas</span>
                    <a href="#" class="flex flex-row items-center text-sky-500">
                        <span class="text-sm">Lebih Lanjut</span>
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 7l5 5m0 0l-5 5m5-5H6" />
                        </svg>
                    </a>
                </div>
                <div class="border p-3 flex flex-row divide-x rounded-lg">
                    <div class="flex flex-row w-3/6 pr-4 space-x-2">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-gray-400" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z" />
                        </svg>
                        <input class="focus:outline-none text-sm font-light w-full" type="text" name="search" placeholder="Cari Mobil Nama, Merk">
                    </div>
                    <div class="flex flex-row w-3/6 pl-4 space-x-2">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-gray-400" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z" />
                          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z" />
                        </svg>
                        <input class="focus:outline-none text-sm font-light w-full" type="text" name="search" placeholder="Cari Mobil Nama, Merk">
                    </div>
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
            <div class="w-4/12 pl-5 space-y-5">
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
        <div class="container mx-auto space-y-10">
            <div class="flex flex-row justify-between items-center">
                <span class="text-2xl font-semibold text-gray-700">Rekomendasi Mobil</span>
                <a href="#" class="flex flex-row items-center text-sky-500 underline underline-offset-8">
                    <span class="">Lihat Semua Mobil</span>
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 7l5 5m0 0l-5 5m5-5H6" />
                    </svg>
                </a>
            </div>
            <div class="flex flex-row space-x-4 justify-center">
                <div class="w-1/3 bg-white rounded-2xl shadow-xl shadow-gray-200/50" v-for="n in 3">
                    <div class="h-64">
                        <img class="object-cover w-full h-full rounded-t-2xl" src="/car-recomended.jpeg" alt="Mobil">
                    </div>
                    <div class="p-4 divide-y space-y-5">
                        <div class="space-y-4">
                            <div class="flex space-x-4">
                                <a class="bg-green-500 text-white text-sm font-semibold px-3 py-1 rounded-lg" href="#">Ready Stock</a>
                                <a class="bg-blue-500 text-white text-sm font-semibold px-3 py-1 rounded-lg" href="#">Verified</a>
                            </div>
                            <p class="font-semibold text-gray-700 truncate">HONDA ALL NEW CR-V 2WD 2.0 AT BENSIN 2.0 BLA BLA BLA</p>
                            <div class="flex flex-row space-x-2">
                                <div class="flex flex-row items-center space-x-1">
                                    <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 text-gray-400" viewBox="0 0 20 20" fill="currentColor">
                                      <path fill-rule="evenodd" d="M5.05 4.05a7 7 0 119.9 9.9L10 18.9l-4.95-4.95a7 7 0 010-9.9zM10 11a2 2 0 100-4 2 2 0 000 4z" clip-rule="evenodd" />
                                    </svg>
                                    <p class="text-xs text-gray-700">KABUPATEN BANYUMAS</p>
                                </div>
                                <div class="flex flex-row items-center space-x-1">
                                    <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 text-gray-400" viewBox="0 0 20 20" fill="currentColor">
                                      <path fill-rule="evenodd" d="M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-7-4a1 1 0 11-2 0 1 1 0 012 0zM9 9a1 1 0 000 2v3a1 1 0 001 1h1a1 1 0 100-2v-3a1 1 0 00-1-1H9z" clip-rule="evenodd" />
                                    </svg>
                                    <p class="text-xs text-gray-700">Auto</p>
                                </div>
                                <div class="flex flex-row items-center space-x-1">
                                    <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 text-gray-400" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3.055 11H5a2 2 0 012 2v1a2 2 0 002 2 2 2 0 012 2v2.945M8 3.935V5.5A2.5 2.5 0 0010.5 8h.5a2 2 0 012 2 2 2 0 104 0 2 2 0 012-2h1.064M15 20.488V18a2 2 0 012-2h3.064M21 12a9 9 0 11-18 0 9 9 0 0118 0z" />
                                    </svg>
                                    <p class="text-xs text-gray-700">88.75 KM</p>
                                </div>
                            </div>
                        </div>
                        <div>
                            <div class="flex flex-row items-center justify-between mt-4">
                                <div class="flex flex-col">
                                    <span class="font-light text-sm text-gray-500">Harga</span>
                                    <span class="text-orange-500 text-lg font-bold font-sans">Rp. 135.500.000,-</span>
                                </div>
                                <div>
                                    <a class="bg-sky-500 p-3 text-sm font-semibold text-white rounded" href="#">Lihat Mobil</a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <div class="bg-white">
        <div class="container mx-auto pt-28 pb-10">
            <div class="text-center space-y-14">
                <div class="space-y-4">
                    <p class="text-3xl text-gray-700 font-bold">Bagaimana cara kerja Moladin?</p>
                    <p class="text-gray-700 font-light">Semua proses transaksi di Moladin serba mudah. Lihat detailnya di sini!</p>
                </div>
                <div class="space-x-4">
                    <a class="bg-sky-600 text-white text-sm py-4 px-8 font-semibold rounded-lg" href="#">Jual Mobil Bekas</a>
                    <a class="text-gray-700 text-sm py-4 px-8 font-semibold rounded-lg border" href="#">Beli Mobil Bekas</a>
                </div>
            </div>
        </div>
    </div>

    
  </div>
</template>
<script>
    
    export default {
        data() {
            return {
              options: {
                responsive: [
                  { end: 576, size: 1 },
                  { start: 576, end: 768, size: 2 },
                  { start: 768, end: 992, size: 3 },
                  { size: 4 },
                ],
                list: {
                  // 1200 because @media (min-width: 1200px) and therefore I want to switch to windowed mode
                  windowed: 1200,

                  // Because: #app {padding: 80px 24px;}
                  padding: 24,
                },
                position: {
                  start: 2,
                },
                autoplay: { play: true, repeat: true, speed: 2500 },
              },
              items: [
                { title: "Item 0", content: "Content item with description" },
                { title: "Item 1", content: "Content item with description" },
                { title: "Item 2", content: "Content item with description" },
              ],
            };
        },
    }
</script>
