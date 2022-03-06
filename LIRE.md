- 👋 Hi, I’m @wassdd93100
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
wassdd93100/wassdd93100 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
Classe Tiktok

Entrées

langue - Auto-explicatif
région - Auto-explicatif
cookie - Le cookie TikTok contenant les parameters_v_web_id. S'il n'est pas fourni, le paramètre sera généré.
__init__(self, language='en', region='IN', cookie=None)
Obtenez des vidéos tendance

Entrées

count - Nombre de vidéos à récupérer
getTrending(self, count=30)
Obtenir l'utilisateur

Entrées

user_name - Nom d'utilisateur, par exemple -fcbarcelona
getUserByName(self, user_name)
Obtenir Des Vidéos Par Nom D'utilisateur

Entrées

user_name - Nom d'utilisateur, par exemple -fcbarcelona
count - Nombre de vidéos à récupérer
getVideosByUserName(self, user_name, count=30)
Obtenir Des Likes Par Nom D'utilisateur

Entrées

user_name - Nom d'utilisateur, par exemple -fcbarcelona
count - Nombre de vidéos à récupérer
getLikesByUserName(self, user_name, count=30)
Obtenir le hashtag

Entrées

hashTag - HashTag, par exemple -#fcbarcelona
getHashTag(self, hashTag)
Obtenir Des Vidéos Par Hashtag

Entrées

hashTag - HashTag, par exemple -#fcbarcelona
count - Nombre de vidéos à récupérer
getVideosByHashTag(self, hashTag, count=30)
Obtenir de la musique

Entrées

music_id - Id à musique, par exemple -6704854531001289474
getMusic(self, music_id)
Obtenir Des Vidéos Par Musique

Entrées

music_id - Id à musique, par exemple -6704854531001289474
count - Nombre de vidéos à récupérer
getVideosByMusic(self, music_id, count=30)
Obtenir Une Vidéo Par Id

Entrées

video_id - Id vidéo, par exemple -6843481669886954757
getVideoById(self, video_id)
Télécharger la vidéo

Entrées

video_id - Id vidéo, par exemple -6843481669886954757
save_path - Chemin dans lequel la vidéo téléchargée doit être enregistrée
downloadVideoById(self, video_id, save_path)
Télécharger la vidéo Pas de filigrane

Entrées

video_id - Id vidéo, par exemple -6843481669886954757
save_path - Chemin dans lequel la vidéo téléchargée doit être enregistrée
downloadVideoByIdNoWatermark(self, video_id, save_path)
