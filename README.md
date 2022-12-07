
#build docker containers 
docker-compose up -d

#fixtures to create initial data
php bin/console doctrine:fixtures:load

#start new adventure 
{$env}/adventure/start
