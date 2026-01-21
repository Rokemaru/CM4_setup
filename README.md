# CM4_setup


sudo mkdir -p /mnt/nas

このコマンドで、mntの下にnasを作成する


sudo apt install cifs-utils -y

もし、CIFSが入ってなければ（なんか、マウントするのに使うやつ）


chmod +x nas_mount.sh
これで、実行権限をそのSHファイルに付与する

あとはSHファイルをクリックして端末で実行すると、mntのディレクトリの下にnasのファイルが出てくる。出てこないときは再読み込み、再度実行すること！！