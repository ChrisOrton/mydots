curl -fsSL https://tailscale.com/install.sh | sh
sudo tailscale up --login-server https://headscale.ukprivacy.news
curl https://headscale.ukprivacy.news:443/register/xxxxxxxx-xxxxxxxx-xxxxxx
sudo tailscale set --hostname=aibox2


Server
ssh root@headscale.ukprivacy.news

headscale nodes register --key xxxxxxxx-xxxxxxxx-xxxxxx --user boss
headscale nodes list

