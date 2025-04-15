import shutil

# Klasörü hazırlamak (simüle edilmiş bir dosya yapısı)
site_structure = {
    "index.html": "Ana sayfa içeriği",
    "style.css": "Tasarım stilleri",
    "images/ilk_bulusma.jpg": "İlk fotoğraf",
    "images/ilk_cicek.jpg": "Çiçekli fotoğraf",
    "video/ilk_sinema.mp4": "İlk sinema videosu",
}

# Basitçe klasör yapısını oluştur
root_dir = "/mnt/data/omernisa_site"
shutil.os.makedirs(root_dir, exist_ok=True)
shutil.os.makedirs(f"{root_dir}/images", exist_ok=True)
shutil.os.makedirs(f"{root_dir}/video", exist_ok=True)

# Klasör yapısını göster
shutil.os.listdir("/mnt/data")
