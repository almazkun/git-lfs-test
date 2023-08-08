# git-lfs-test
Test Git LFS 

1. Install Git LFS
    * `brew install git-lfs`
1. Initialize Git LFS
    * `git lfs install`
1. Track files
    * `git lfs track "*.bin"`
1. Add files
    * `git add .gitattributes`
1. Commit files
    * `git commit -m "Use Git LFS"`
1. Push files
    * `git push`
1. Create big file
    * `dd if=/dev/zero of=output.bin bs=1m count=101`
1. Add big files
    * `git add output.bin`
1. Commit big files
    * `git commit -m "Add big file"`
1. Push big files
    * `git push`