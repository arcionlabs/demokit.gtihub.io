
- Setup dbeaver

```bash 
docker pull dbeaver/cloudbeaver
docker volume create dbeaver
docker run -d --name dbeaver1 --net=arcnet -p 8978:8978 -v dbeaver:/opt/cloudbeaver/workspace dbeaver/cloudbeaver
```

- Run

point browser to http://localhost:8978
id:
password:


