# ProyectoBiologia
# 1. Asegúrate de estar en el directorio del repositorio
cd /workspaces/ProyectoBiologia

# 2. Configura el repositorio remoto con SSH
git remote set-url origin git@github.com:sirspinoza97/ProyectoBiologia.git

# 3. Configura git pull para usar rebase
git config pull.rebase true

# 4. Crea un alias para sincronización automática
git config alias.sync '!git pull origin main && git push origin main'

# 5. Verifica que el remoto está configurado correctamente
git remote -v
