curl -LsSf https://astral.sh/uv/install.sh | sh && source ~/.bashrc && uv python install 3.12 && uv venv && source .venv/bin/activate   && uv pip install numpy matplotlib jupyter


sudo apt install unzip && curl -fsSL https://fnm.vercel.app/install | bash && source ~/.bashrc && fnm install 22 && source ~/.bashrc && fnm use 22 && npm install -g pnpm && source ~/.bashrc && node -e "console.log('Node', process.version)"

curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh && source ~/.bashrc && rustc --version && cargo --version

uv pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu124
test line
