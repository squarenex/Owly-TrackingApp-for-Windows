# One-time setup: publish .exe + .dmg from private repo → this public repo
#
# 1) Create Fine-grained PAT (GitHub → Settings → Developer settings → Personal access tokens)
#    - Resource owner: account that can write to squarenex/Staffy-Staff-Tracking
#    - Repository access: squarenex/Staffy-Staff-Tracking
#    - Permissions: Contents = Read and write
#
# 2) In PRIVATE repo kashifg4171/Squarenex_Staff_Tracking_Desktop:
#    Settings → Secrets and variables → Actions → New repository secret
#
#    Name:  PUBLIC_RELEASES_TOKEN
#    Value: <paste PAT>
#
#    Optional:
#    Name:  PUBLIC_RELEASES_REPO
#    Value: squarenex/Staffy-Staff-Tracking
#
# 3) Push to private main (or Actions → Build Desktop Releases → Run workflow)
# 4) Open https://github.com/squarenex/Staffy-Staff-Tracking/releases
#    You should see ONLY Staffy-Windows-Setup-*.exe and Staffy-macOS-*.dmg
