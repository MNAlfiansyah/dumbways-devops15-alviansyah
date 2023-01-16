<!-----

You have some errors, warnings, or alerts. If you are using reckless mode, turn it off to see inline alerts.
* ERRORs: 0
* WARNINGs: 0
* ALERTS: 20

Conversion time: 4.868 seconds.


Using this Markdown file:

1. Paste this output into your source file.
2. See the notes and action items below regarding this conversion run.
3. Check the rendered output (headings, lists, code blocks, tables) for proper
   formatting and use a linkchecker before you publish this page.

Conversion notes:

* Docs to Markdown version 1.0β34
* Mon Jan 16 2023 05:00:29 GMT-0800 (PST)
* Source doc: INTRODUCTION TO DEVOPS
* This document has images: check for >>>>>  gd2md-html alert:  inline image link in generated source and store images to your server. NOTE: Images in exported zip file from Google Docs may not appear in  the same order as they do in your doc. Please check the images!

----->


<p style="color: red; font-weight: bold">>>>>>  gd2md-html alert:  ERRORs: 0; WARNINGs: 0; ALERTS: 20.</p>
<ul style="color: red; font-weight: bold"><li>See top comment block for details on ERRORs and WARNINGs. <li>In the converted Markdown or HTML, search for inline alerts that start with >>>>>  gd2md-html alert:  for specific instances that need correction.</ul>

<p style="color: red; font-weight: bold">Links to alert messages:</p><a href="#gdcalert1">alert1</a>
<a href="#gdcalert2">alert2</a>
<a href="#gdcalert3">alert3</a>
<a href="#gdcalert4">alert4</a>
<a href="#gdcalert5">alert5</a>
<a href="#gdcalert6">alert6</a>
<a href="#gdcalert7">alert7</a>
<a href="#gdcalert8">alert8</a>
<a href="#gdcalert9">alert9</a>
<a href="#gdcalert10">alert10</a>
<a href="#gdcalert11">alert11</a>
<a href="#gdcalert12">alert12</a>
<a href="#gdcalert13">alert13</a>
<a href="#gdcalert14">alert14</a>
<a href="#gdcalert15">alert15</a>
<a href="#gdcalert16">alert16</a>
<a href="#gdcalert17">alert17</a>
<a href="#gdcalert18">alert18</a>
<a href="#gdcalert19">alert19</a>
<a href="#gdcalert20">alert20</a>

<p style="color: red; font-weight: bold">>>>>> PLEASE check and correct alert issues and delete this message and the inline alerts.<hr></p>


**INTRODUCTION TO DEVOPS**



1. **Definisi DevOps**

    **Devops** adalah sebuah kultur dimana tim pengembang(development) dan tim operasi(operations) berkolaborasi dalam pengembangan aplikasi, yang membuat pengembangan aplikasi menjadi lebih cepat dan efisien.

2. **Lifecycle DevOps**

**	**

<p id="gdcalert1" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image1.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert2">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image1.png "image_tooltip")




1. Plan

        Pada tahap Plan, seluruh perencanaan dan perancangan untuk pengembangan aplikasi akan dilakukan. Biasanya, tahap ini akan dipimpin oleh seorang Project Manager. Aturan, persyaratan, dan feedback dari stakeholders dan user akan dikumpulkan untuk membuat roadmap project. Tools yang umum digunakan untuk melakukan tracking diantaranya adalah Jira, ClickUp, dan lainnya.

2. Code

        Pada tahap ini, developer akan mulai menuliskan kode untuk aplikasi yang akan dibuat. Setelah selesai menulis kode, developer kemudian akan menyimpan kode tersebut ke repository github menggunakan proses push.

3. Build

             Setelah kode dipush ke repository, tahap selanjutnya adalah build. Build merupakan proses mengubah kode yang ditulis oleh developer menjadi sebuah aplikasi yang siap dijalankan. Sebelum melakukan build, developer lain biasanya akan melakukan diskusi untuk memberikan feedback dan review terhadap kode yang telah ditulis. Setelah selesai diskusi, build aplikasi akan dilakukan menggunakan alat yang sesuai dengan jenis aplikasi yang akan dibuat. Contohnya, jika ingin menjadikan aplikasi sebagai image dapat menggunakan Docker.

4. Test

             Setelah build aplikasi selesai, tahap selanjutnya adalah melakukan pengujian. Pengujian ini bertujuan untuk mengetahui apakah aplikasi yang dibuat memenuhi kriteria yang ditetapkan, berfungsi dengan baik, dan sesuai dengan desain yang diinginkan. Jika terdapat kekurangan atau masalah, proses akan berhenti pada tahap ini dan perbaikan akan dilakukan. Namun jika aplikasi sudah sesuai dengan kriteria yang ditetapkan, maka lanjut ke tahap release.

5. Release

              Pada tahap Release, aplikasi yang sudah lulus pengujian akan diberi label atau nomor versi. Setelah itu, aplikasi tersebut akan di-deploy.

6. Deploy

              Deploy adalah proses menempatkan atau menyebarkan aplikasi yang dibuat, sehingga dapat diakses oleh user. Alat yang sering digunakan untuk proses ini adalah AWS, CodeDeploy dan Jenkins.

7. Operate

              Pada tahap Operate, tim Operation akan memastikan bahwa aplikasi dan infrastruktur berjalan dengan baik. Data performance, error, dan lainnya juga akan dilihat. Jika terdapat kesalahan atau bug, user dapat memberikan feedback yang kemudian akan menjadi bahan pertimbangan untuk pengembangan aplikasi selanjutnya.

8. Monitor

             Tahap Monitor merupakan tahap terakhir dari DevOps Lifecycle. Pada tahap ini, tim akan mengumpulkan semua data performance, error, dan feedback yang telah dikumpulkan sebelumnya. Kemudian, data tersebut akan digunakan untuk melakukan evaluasi atau introspeksi terhadap aplikasi yang dikembangkan. Selain itu, tim juga akan memantau pipeline yang dibuat untuk menghindari adanya bottlenecks yang dapat menghambat produktivitas pengembangan aplikasi di masa yang akan datang.

3. **Instalasi Ubuntu Server**
* Pertama-tama tahap yang harus dilakukan adalah mendownload vm dan ubuntu live server, disini saya menggunakan vm multipass, kalian bisa mendownload dilink dibawah ini :

    Ubuntu Live Server : [https://ubuntu.com/download/server#downloads](https://ubuntu.com/download/server#downloads)


    Multipass : [https://multipass.run/install](https://multipass.run/install)


        Setelah proses download keduanya selesai sekarang saatnya untuk install VM kita

* Installation VM

    Klik langsung `Continue`


    

<p id="gdcalert2" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image2.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert3">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image2.png "image_tooltip")



    Selanjutnya `Continue`


    

<p id="gdcalert3" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image3.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert4">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image3.png "image_tooltip")



    Klik Continue dan Agree saja termsnya


    

<p id="gdcalert4" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image4.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert5">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image4.png "image_tooltip")



    

<p id="gdcalert5" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image5.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert6">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image5.png "image_tooltip")



    Disini kalian pilih hdd yang akan diinstall VMnya, jika sudah dipilih langsung saja klik `continue`


    

<p id="gdcalert6" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image6.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert7">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image6.png "image_tooltip")



    Disini kalian akan memilih install location vm multipass, jika sudah klik `install`


    

<p id="gdcalert7" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image7.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert8">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image7.png "image_tooltip")



    Jika berhasil terinstall maka akan muncul instalasi sukses


    

<p id="gdcalert8" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image8.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert9">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image8.png "image_tooltip")



    Selanjutnya kita masuk ketahap config IP static

* Setup multipass dan setting ip statis

    Pertama kita akan membuat vm kita dengan command seperti dibawah.


    

<p id="gdcalert9" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image9.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert10">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image9.png "image_tooltip")



    Setelah kita berhasil membuat vm selanjutnya kita cek apakah vm kita sudah running.


    

<p id="gdcalert10" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image10.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert11">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image10.png "image_tooltip")



Selanjutnya kita akan masuk kedalam vm yang telah kita buat 


    

<p id="gdcalert11" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image11.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert12">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image11.png "image_tooltip")



    Setelah masuk kita pastikan ip address vm kita, dan kita save ip vm kita


    

<p id="gdcalert12" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image12.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert13">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image12.png "image_tooltip")



    Lalu kita masuk ke folder /etc/netplan


    

<p id="gdcalert13" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image13.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert14">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image13.png "image_tooltip")



    Command ls untuk melihat isi file yang ada pada folder /netplan


    

<p id="gdcalert14" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image14.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert15">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image14.png "image_tooltip")



    Lalu kita buka dengan command `sudo nano 50-cloud-init.yaml`


    

<p id="gdcalert15" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image15.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert16">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image15.png "image_tooltip")



    Setelah terbuka bisa kita lihat kalau setting ip vm kita dhcp, selanjutnya kita akan edit agar ipnya tidak dapat berubah-ubah.


    

<p id="gdcalert16" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image16.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert17">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image16.png "image_tooltip")



    Kalian bisa mengikuti setup dibawah ini


    

<p id="gdcalert17" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image17.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert18">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image17.png "image_tooltip")



    Setelah kalian save file .yaml tersebut selanjutnya kita akan apply perubahan ipconfig yang telah kita lakukan dengan command `sudo netplan apply`


    

<p id="gdcalert18" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image18.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert19">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image18.png "image_tooltip")



    Step terakhir adalah mengetes apakah vm kita sudah terhubung dengan google.


    

<p id="gdcalert19" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image19.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert20">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image19.png "image_tooltip")



    Dan servernya juga sudah terhubung dengan local network kita.


    

<p id="gdcalert20" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image20.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert21">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image20.png "image_tooltip")

