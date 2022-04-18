// 指定分支 - on branch specified
git submodule update --init --remote --rebase --single-branch
git submodule update

// 不指定分支
git submodule update --init --rebase --single-branch --recursive
