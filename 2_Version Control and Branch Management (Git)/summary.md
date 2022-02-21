<h1>(2) Version Control and Branch Management (Git)</h1>

<h2>Versioning</h2>
<p>
    Versioning adalah mengatur versi dari source code program. Hal ini terjadi ketika kita mempunyai file yang mungkin harus terdapat revisi yang tidak hanya sekali yang mana akan membuat file kita menjadi bertumpuk. 
    Cikal Bakal VCS (Version Control System) :
    <ol>
        <li>Singel User</li>
        <li>Centralized</li>
        <li>Distributed</li>
    </ol>

    Dalam memulai versioning dapat menggunakan tools berikut :
    <ul>
        <li>GIT</li>
        <li>GitHub</li>
        <li>VSCode</li>
    </ul>

</p>

<h2>GIT</h2>
<p>
<h3>Introducing</h3>
    Git merupakan salah satu version control system populer yang digunakan developer dalam mengembangkan software dalam kolaborasi. Git merekam setiap perubahan file. Github merupakan git hosting servis dalam membuat repository yang akan digunakan dalam mengerjakan project. Git dapat diinstall melalui Mac, Windows, dan Linux. 
<h3>Setting Up</h3>
    Sebelum masuk ke repository, file harus melalui taging area terlebih dahulu. File akan masuk ke working directory terlebih dahulu, lalu dengan perintah git add. Kemudian file akan masuk ke staging area, lalu dengan perintah git commit maka file akan masuk ke repository yang ada di github.
<h3>Perintah-perintah GIT</h3>
<ul>
    <li>Untuk setting up dapat menggunakan perintah git init, git clone, dan config</li>
    <li>Untuk save changes menggunakan perintah git status, add, commit, stash, dan diff</li>
    <li>Untuk inspecting Repository bisa menggunakan git log, checkout,dan reset</li>
    <li>Untuk proses Syncing menggunakan git push, fetch, dan pull</li>
    <li>Untuk membuat branches bisa menggunaka perintah git branching, merge,</li>
</ul>
</p>

<h2>Workflow Collaboration</h2>
<p>
    Dalam hal ini bertujuan untuk memahami alur kerja yang tepat untuk berkolaborasi dalam github maupun gitlab. Cara agar alur kerja tetap optimal yaitu :
    <ol>
        <li>Biarkan master branch tidak terganggu</li>
        <li>Hindari pengeditan langsung pada development</li>
        <li>Terapkan featur pada branch development saja</li>
        <li>Terapkan development ke master saat sudah selesai</li>
    </ol>
</p>
