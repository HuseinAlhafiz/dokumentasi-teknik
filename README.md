# 📍 Tentang Backoffice

## 1. Petunjuk Instalasi

**Laravel Project Setup Guide**

{% hint style="info" %}
This guide will walk you through the steps required to set up a Laravel project on your local machine. Laravel is a popular PHP framework for building web applications.
{% endhint %}

**Prerequisites**

> Before you begin, make sure you have the following installed on your machine:\
> \- required PHP v8.0 or greater\
> \- required Composer v2.5.8 or greater\
> \- required Node.js v18 (with npm or yarn) or greater\
> \- required Git v2.34.1 or greater\
> \- optional Docker v25.0.2 or greater

**Getting Started**

1. Clone the repository

```
sh
git clone "link repository"
```

2. Navigate to the project directory

```
sh
cd "project directory"
```

3\. Install PHP dependencies using composer

```
sh
cd composer install
```

4\. Copy .env.example to .env

```
sh
cp .env.example .env
```

5\. Generate application key

```
sh
php artisan key:generate
```

6\. Install javascript using npm or yarn

```
sh
npm install
or
yarn install
```

7\. Compile assets

```
sh
for local development
npm run dev
or
yarn dev
```

8\. Setup your database configuration file. If your are using docker, you can skip this step.

```
sh
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=your_database_name
DB_USERNAME=your_database_username
DB_PASSWORD=your_database_password
```

9\. Migrate the database

```
sh
php artisan migrate
```

10\. Serve application

```
sh
php artisan server
```



**Additional Configuration**

{% hint style="info" %}
\- Environment Configuration: Update the .env file as per your environment settings (e.g., APP\_DEBUG, APP\_URL, etc.).\
\- Database Configuration: Modify the database configuration in the .env file according to your requirements.\
\- Cache Configuration: You can configure caching options in the .env file.\
\- Queue Configuration: If your application uses queues, configure the queue driver in the .env file.
{% endhint %}

\
**Run Using Docker**

For those of u who prefer using docker when serving the application, please follow these steps below:

1\. Follow the prior step until you are at step\
2\. Start the docker container

```
# run usign docker
docker compose up -d
# or using docker-compose
docker-compose up -d
```

3\. Migrate the database using sail

```
sh
./sail artisan migrate
```

### 3. TUJUAN

Tujuan utama Program Backoffice Kedaireka adalah untuk mendorong terjadinya kerjasama yang saling menguntungkan dan berkelanjutan antara dosen sebagai pihak pengusul dengan dengan mitra sesuai dengan deskripsi masing-masing skema.

### 4. AKTOR

<table><thead><tr><th width="72">No</th><th width="188">User Category</th><th>User Main Activity</th></tr></thead><tbody><tr><td>1</td><td>Admin</td><td>• Mengakses seluruh fitur pengusul.show-menu<br>• Mengakses seluruh fitur pengusul-menu<br>• Mengakses seluruh fitur perguruan-tinggi.show-menu<br>• Mengakses seluruh fitur perguruan-tinggi-menu<br>• Mengakses seluruh fitur action-verifikasi<br>• Mengakses seluruh fitur action-revert-status-verifikasi<br>• Mengakses seluruh fitur kontrak.show-menu<br>• Mengakses seluruh fitur seminar-admin-dksi</td></tr><tr><td>2</td><td>Pengusul</td><td>• Mengakses seluruh fitur pengusul-dashboard<br>• Mengakses seluruh fitur pengusul-pengajuan<br>• Mengakses seluruh fitur pengusul-show-proposal<br>• Mengakses seluruh fitur pengusul-ajukan-proposal</td></tr><tr><td>3</td><td>Tim Reviewer</td><td>• Mengakses seluruh fitur index-tugas-menu<br>• Mengakses seluruh fitur show-tugas-menu</td></tr><tr><td>4</td><td>Unit Pengelola (KUP) di Perguruan Tinggi</td><td>• Mengakses seluruh fitur action-verifikasi<br>• Mengakses seluruh fitur action-revert-status-verifikasi<br>• Mengakses seluruh fitur index-tugas-menu<br>• Mengakses seluruh fitur show-tugas-menu<br>• Mengakses seluruh fitur up-index-proposal-menu<br>• Mengakses seluruh fitur up-show-proposal-menu<br>• Mengakses seluruh fitur up-index-kontrak-menu<br>• Mengakses seluruh fitur up-show-kontrak-menu<br>• Mengakses seluruh fitur up-verif-pra-kontrak</td></tr></tbody></table>

### 5. FITUR YANG DIKEMBANGKAN

<table><thead><tr><th width="81">No</th><th width="167">Epic</th><th>Feature</th><th></th></tr></thead><tbody><tr><td></td><td></td><td>User</td><td>Admin</td></tr><tr><td>1</td><td>Perguruan Tinggi</td><td>Profiling oleh Admin<br>- Daftar Pengusul<br>- Daftar Industri<br>- Total Kolaborasi dengan Industri<br>- Total Pendanaan</td><td>-</td></tr><tr><td>2</td><td>Mitra</td><td>Login<br>- Daftar Pengusul<br>- Daftar Proposal<br>- Status Pendanaan<br></td><td>Profiling oleh Admin<br>- Daftar Pengusul<br>- Daftar Proposal<br>- Daftar Mitra<br>- Total Kolaborasi dengan Perguruan Tinggi<br>- Total Pendanaan</td></tr><tr><td>3</td><td>Pengusul</td><td>Login<br>- Daftar Proposal<br>- Status Pendanaan<br></td><td>Profiling oleh Admin<br>- Daftar Proposal<br>- Status Pendanaan<br></td></tr></tbody></table>





<table><thead><tr><th width="209">Document Owner</th><th>Dimas Ahmad, M. Hilmy, M. Zulkifli, Rian A.P, Husein Alhafiz</th></tr></thead><tbody><tr><td>Designer</td><td>Novita Rahmadhani</td></tr><tr><td>Developers</td><td>Ahmad Jalu F. N. H, Anreas Nugroho, Bintang Rahmatullah, Michael Mervin R, Reza Irvando, Umar Hadi Mukti</td></tr><tr><td>Quality Assurance</td><td>M. Fadly Febrian, M. Ibnu Al Hanif</td></tr><tr><td>Delivery Date</td><td>-</td></tr><tr><td>Sign off Date</td><td>-</td></tr></tbody></table>

The Mailchimp Marketing API provides programmatic access to Mailchimp data and functionality, allowing developers to build custom features to do things like sync email activity and campaign analytics with their database, manage audiences and campaigns, and more.







> — From the [Mailchimp Marketing API docs](https://mailchimp.com/developer/marketing/docs/fundamentals/)



## Quick links

{% content-ref url="tentang-backoffice/what-we-do.md" %}
[what-we-do.md](tentang-backoffice/what-we-do.md)
{% endcontent-ref %}

{% content-ref url="tentang-backoffice/our-features.md" %}
[our-features.md](tentang-backoffice/our-features.md)
{% endcontent-ref %}

## Get Started

We've put together some helpful guides for you to get setup with our product quickly and easily.

{% content-ref url="fundamentals/getting-set-up/" %}
[getting-set-up](fundamentals/getting-set-up/)
{% endcontent-ref %}

{% content-ref url="fundamentals/getting-set-up/setting-permissions.md" %}
[setting-permissions.md](fundamentals/getting-set-up/setting-permissions.md)
{% endcontent-ref %}

{% content-ref url="fundamentals/getting-set-up/inviting-members.md" %}
[inviting-members.md](fundamentals/getting-set-up/inviting-members.md)
{% endcontent-ref %}
