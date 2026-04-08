# MustafaKucukbas_RollABallGame
# EN

## Game Development Diary
Since this project is generally based on basic mechanics, it honestly didn't take much of my time. I quickly completed all the required steps. I made sure to keep the project folder structure (Scripts, Materials, Prefabs, etc.) as clean and organized as possible.

## Completed Steps
- **Setting up the game & play area:** I created the basic scene, walls, and the main play area. 
- **Moving the player & camera:** I wrote the necessary physics scripts for the ball's movement and made sure the camera followed the ball from the right angle. Since these are fundamental scripting tasks, it was pretty effortless.
- **Creating collectibles:** I scattered the collectible objects across the scene. I set them up using the prefab logic so I could control all of them from a single place easily.

## Bonus & Level Design
Just rolling a ball on an empty, flat ground looked a bit too plain and amateur, so I designed a park area using extra assets. By placing objects like a swing and a slide, I did a mini level design and pushed the visual quality of the game up a notch.

## Errors, Fixes and AI Usage
I didn't encounter any challenging errors regarding coding or mechanics; everything worked perfectly. There is just one minor detail: when we lose the game, the player object is destroyed in the scene, which causes the camera to lose its target and throw a small missing reference error. Honestly, since the game is already over at that point, I didn't feel the need to write extra code to fix it because it doesn't break the gameplay at all.

Other than that, I had a minor collider issue with the park assets I used for the level design. For instance, when I attached a normal box collider to the slide, the ball couldn't pass through the empty spaces underneath it. I asked an AI how to add colliders to such complex 3D models without blocking the empty gaps. It told me to add a Mesh Collider and uncheck the Convex setting. I tried it and got the exact result I wanted.

## GitHub Structure
The very first thing I did when starting the project was adding a .gitignore file, so unnecessary files like Library or temp folders aren't cluttering the repository. I also kept the commit history meaningful, committing step-by-step rather than dumping everything at once.

---

# TR

## Game Development Diary
Bu proje genel olarak basit mekanikler üzerine kurulu olduğu için açıkçası pek vaktimi almadı hızlı bir şekilde benden istenen bütün adımları tamamladım. Proje içindeki dosya yapısını (Scripts, Materials, Prefabs vs) olabildiğince clean ve düzenli tutmaya özen gösterdim.

## Completed Steps
- **Setting up the game & play area:** Oyunun temel sahnesini duvarlarını ve oynanış alanını oluşturdum. 
- **Moving the player & camera:** Topun hareketi için gerekli fizik kodlarını yazdım kameranın da topu doğru açıyla takip etmesini sağladım. Buralar zaten temel script işleri olduğu için pek uğraştırmadı.
- **Creating collectibles:** Toplanabilir objeleri sahneye dağıttım prefab mantığıyla hepsini tek bir yerden kontrol edilebilir şekilde ayarladım.

## Bonus & Level Design
Sadece boş bir zemin üstünde top yuvarlamak çok yavan ve amatör duracağı için ekstra assetler kullanarak bir park alanı tasarladım. Salıncak kaydırak gibi objelerle mini bir level design yapıp oyunun görsel kalitesini bir tık yukarı taşıdım.

## Errors, Fixes and AI Usage
Kodlama veya mekanik kısmında uğraştıran bir hatayla karşılaşmadım her şey stabil çalıştı. Sadece küçük bir detay var oyunu kaybettiğimizde player objesi sahnede destroy edildiği için kamera takip edeceği target'ı kaybediyor ve ufak bir missing reference hatası veriyor. Ama o sırada zaten oyun bitmiş olduğu için ekstra kod yazıp bunu düzeltmeye gerek duymadım açıkçası çünkü oynanışı bozan bir durum yok. 

Bunun dışında level design yaparken eklediğim park assetlerinde ufak bir collider problemi yaşadım. Örneğin kaydırağa normal box collider attığımda top altındaki boşluklardan geçemiyordu. Yapay zekaya bu tarz şekilli 3d modellere boşlukları kapatmadan nasıl collider ekleyebileceğimi sordum. Bana Mesh Collider ekleyip Convex ayarını kapatmamı söyledi. Denedim ve istediğim sonucu aldım. 

## GitHub Structure
Projeye başlarken ilk iş .gitignore ekledim o yüzden repoda Library veya temp gibi gereksiz dosyalar kalabalık yapmıyor. Commit geçmişini de mantıklı parçalara bölerek aşama aşama attım.

