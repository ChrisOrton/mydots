   25  curl -fsSL https://tailscale.com/install.sh | sh
   26  sudo apt install curl
   27  curl -fsSL https://tailscale.com/install.sh | sh
   30  sudo tailscale up --login-server https://headscale.ukprivacy.news
  21  curl https://headscale.ukprivacy.news:443/register/xxxxxxxx-xxxxxxxx-xxxxxx
   23  sudo tailscale set --hostname=aibox2


Server
ssh root@headscale.ukprivacy.news

   94  headscale nodes register --key xxxxxxxx-xxxxxxxx-xxxxxx --user boss
   95  headscale nodes list
   96  history

