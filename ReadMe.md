Developer modifies HTML
        ↓
git add / commit / push
        ↓
GitHub detects push
        ↓
GitHub Actions workflow starts
        ↓
GitHub finds your EC2 self-hosted runner
        ↓
EC2 runner downloads repository
        ↓
docker build
        ↓
New Docker image
        ↓
Old container stopped
        ↓
New container started
        ↓
Website updated