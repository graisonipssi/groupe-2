# Clone le repository
git clone https://github.com/graisonipssi/groupe-2.git
cd groupe-2

# Crée la structure de base
echo "# Histoire du Hero's Journey - Groupe 2" > README.md
mkdir chapitres
touch chapitres/.gitkeep

# Configure ton Git (si pas déjà fait)
git config --global user.name "Ton Nom"
git config --global user.email "ton.email@example.com"

# Premier commit
git add .
git commit -m "Initial commit: Structure du projet"
git push origin main
