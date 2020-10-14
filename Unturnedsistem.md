<h1><a id="user-content-server-hosting" class="anchor" aria-hidden="true" href="#unturned-problemi"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>SteamCMD Unturned Sunucu Kurulumu</h1>
<p>Yeni gelen güncelleme ile sunucunuzu açmaya çalıştığınız da eğer <strong>Hosting dedicated servers using client files has been deprecated since June 2019.</strong> hatası ile karşılaşıyorsanız. bu adımları izleyerek sunucunuzu hızlıca başlatabilirsiniz.</p>

<h2><a id="user-content-how-to-install-steamcmd-on-windows" class="anchor" aria-hidden="true" href="#steamcmd-nasil-kurulur"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>SteamCMD Nasıl Kurulur</h2>

<ol>
<li>VDS Sunucunuz üzerinden<a href="https://steamcdn-a.akamaihd.net/client/installer/steamcmd.zip" rel="nofollow"> Bu Mesaja Tıklayarak SteamCMD İndirin.</a></li>
<li>Bir klasör oluşturun ve inen zip dosyasını klasörün içine çıkartın.</li>
<li><code>steamcmd.exe</code> Çalıştırın</li>
</ol>
<p>İşlemleri gerçekleştirdiyseniz <a href="#steamcmd-ile-unturned-sunucusu-kurma">SteamCMD ile Unturned Sunucusu Nasıl Kurarım?</a> aşamasına geçebilirsiniz.</p>

<h2><a id="user-content-how-to-install-server-using-steamcmd" class="anchor" aria-hidden="true" href="#steamcmd-ile-unturned-sunucusu-kurma"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>SteamCMD ile Unturned Sunucusu Nasıl Kurarım?</h2>

<ol>
<li>
<p>Anonim olarak steamcmd ye giriş yapın.:</p>
<pre><code> login anonymous
</code></pre>
</li>
<li>
<p>Sunucuyu indirin:</p>
<pre><code> app_update 1110390
</code></pre>
<p><em>Not: Oyuna güncelleme geldiğinde de bu komut ile sunucunuzu güncelleyeceksiniz.</em></p>
</li>
<li>
<p>SteamCMD yi kapatın:</p>
<pre><code> quit
</code></pre>
</li>
<li>
<p>Sunucu dosyalarına erişmek için &gt; steamapps &gt; common &gt; U3DS konumuna girebilirsiniz.</p>
</li>
</ol>
<p>İşlemleri gerçekleştirdiyseniz <a href="#sunucumu-nasil-baslatirim">Sunucumu nasıl başlatırım</a> aşamasına geçiş yapabilirsiniz.</p>

<h2><a id="user-content-how-to-launch-server-on-windows" class="anchor" aria-hidden="true" href="#sunucumu-nasil-baslatirim"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Sunucumu Nasıl Başlatırım?</h2>

<ol>
<li>
<p>SteamCMD Konumuna gidin &gt; steamapps &gt; common &gt; U3DS klasörüne girin</p>
</li>
<li>
<p>Sağ tıklayarak yeni Metin Belgesi oluşturun.</p>
</li>
<li>
<p>"Yeni Metin Belgesi.txt" ismini "Sunucum.bat" olarak değiştirin.</p>
</li>
<li>
<p>Yeni oluşturduğunuz (<code>Sunucum.bat</code>) scriptine sağ tıklayarak düzenleyi seçin.</p>
</li>
<li>
<p>Açılan metin belgesine alt kısımda bulunan komutu girin:</p>
<pre><code> start "" "%~dp0ServerHelper.bat" +InternetServer/Sunucum
</code></pre>
<p><em>Not: Kodun sonundaki /Sunucum sizin sunucunuzun klasör ismini temsil etmektedir.</em></p>
</li>
<li>
<p>Değişiklikleri kaydedin..</p>
</li>
<li>
<p>Oluşturduğunuz .bat scriptini çift tıklayarak çalıştırın.</p>
</li>
<li>
<p>Temiz bir başlangıç için birkere sunucunuz açıldıktan sonra kapatıp tekrar açmalısınız:</p>
<pre><code> shutdown
</code></pre>
<p>"Sunucum" klasörünün oluştuğu konum U3DS &gt; Servers. Bu konuma eski sunucu dosyalarınızı taşıyabilirsiniz..</p>
</li>
</ol>
