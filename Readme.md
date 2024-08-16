### Commands
python3 -m venv llmVenv
python3 -m ipykernel install --user --name=cuda10.1 --display-name="llm-gpt"

pip3 install --pre torch torchvision torchaudio --extra-index-url https://download.pytorch.org/whl/nightly/cpu
