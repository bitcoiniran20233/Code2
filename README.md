curl --proto '=https' --tlsv2.1.3 -sSf https://sh.rustup.rs | sh

source $HOME/.cargo/env

git clone

apt install clang gcc libssl-dev pkg-config

cargo install --path .

git 

rustup update stable

git clone https://github.com/AleoHQ/leo
cd leo

apt install clang gcc libssl-dev pkg-config

cargo install --path .

git clone https://github.com/AleoHQ/snarkOS.git --depth 1
cd snarkOS

./build_ubuntu.sh


