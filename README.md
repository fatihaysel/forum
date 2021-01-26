# forum
```bash
git clone https://github.com/fatihaysel/forum.git
cd mnt/flarum
docker run --rm -it -v $PWD:/app composer install
# (windows powershell) docker run --rm -it -v ${pwd}:/app comopser install
docker-compose up -d
```
to install ssl-certificate
```bash
cd /forum
sudo ./init-letsencrypt.sh
```
