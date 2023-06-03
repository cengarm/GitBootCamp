# GitBootCamp
git_homework

# This repo was created with git commands(git push , pull, merge fetch)

pwd = nerede olduğumuzu gösterir.

cd .. = bir üst klasöre gider.
cd kloser ismi = o klosere geçiş
cd desktop = masaüstü

ls = tüm dosyaları gösterir
ls -a = gizlileri de gösterir

mkdir dosyaName = klasör oluşturma
touch index.html = dosya oluşturma
touch .gitignore = paylaşılmak istemeyenleri bu dosyanın içerisine ismini yazıyorsun. Hiç biri paylaşılmıyor.

git init = bulunmuş olduğumuz klasör içerisinde gizli .git klasörü oluşturuyor bu sayede comitler yapabiliyoruz.

git status = klasör içerisinde yaptıklarımı gösteriyor farklılıkları görebiliyoruz comit yapmadıklarımıızı falan.

git add dosyaAdı = ekleme işlemine yarıyor.
git add . = toplu ekleme işlemi

git commit --m "yapılandeğişiklikMesajı" = add yapılan dosyaları create etti.

git log = logları tutuyor işlemler değişiklikler
git log --oneline = daha kısabilgi gösteriyor.

deneme4 silindi diyelim 
git status yaparak silinenden bir öncekinde ki commit id alarak geri dönebiliyoruz.
git checkout eklendiYazısınınCommitId -- . =  bu sayede silinen bütün dosyayı geri getirebildik.

git diff = dosyada yapılan farklılıkları gösteriyor
git diff doyaName = sadece dosya adında olan değişiklikleri yapıyor.

git checkout master
git checkout -- deneme4.txt -- yapılanları geri alır(silme)

git reset HEAD dosyaName = stagingareaya yollananı geri çalışma alanımıza geri alabiliyoruz.
düzeltmek için git checkout kullanırız.

gir rm dosyaName = dosyayı siliyor. rm = remove
bunu yaptıktan sonra commitlemeyi unutma.
gir rm -r klasörName = klasörleri siliyor.

git mv eskiismi yeniismi = dosyaların ismini değiştirebiliyoruz.
git mv dosyaismi klasörismi/ = dosyayı klasore taşıma

git config --global alias.st status = statu yazmak yerine st yazmamıza yarıyor değişken atama gibi.

------------------------------------------------------
git status
git add . 
git commit --m "bilgi"
git push -u origin master

FOR GITHUB
git remote add origin https://github.com/cengarm/GitBootCamp.git 
origin adında uzak sunucuya göndermek için oluşturdum 

git push -u origin master = master olarak originimize dosyalaru yolladık.

git pull origin master veya dev = başkalarının dosyalarını kendi lokalimize çekiyoruz.

git branch --all

git fetch uzak sunucuda ki branchleri alıyor
git fetch -p = githubta sildiğimiz branchleri localimizde bulunanla karşılaştırıp fazlaysa siliyor

git branch -D brancName = -D elete

git checkout branchName = branchler arası geçiş

git merge nerdenKodlaralıncaksaismi (dev) 
