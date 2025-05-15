# gr-pr 🚀  
Static HTML Website with Docker Support

This project contains a simple, styled HTML website that can be served using Docker via Nginx (or any other method you choose).

---

## 🔧 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/AhemdMahmoud/gr-pr.git
cd gr-pr
```


#2. Build the Docker Image
```
docker build -t gr-pr .
```
3. Run the Container

```
docker run -d -p 8080:80 --name gr-social gr-pr
```
## Now visit: http://localhost:8080 🎉
