# Hosted PowerFX Samples

Sample repository that demonstrates how to host Power Fx in multiple languages

## Getting started

### Compile the .Net code

1. Ensure NET 8.0 SDK is installed to create a .Net Standard 2.0 binary

2. Change to PowerFx module

```bash
cd src/dotnet
```

3. Publish the example Power Fx class

```bash
dotnet publish -c Release  -r win-x64 --sc --framework netstandard2.0
dotnet publish -c Release  -r win-x64 --sc --framework net8.0
```

### NodeJs

To run the NodeJs sample

1. Change to NodeJs source and install dependancies

```
cd src/nodejs
npm install
```

2. Run the app

```
node main.js
```

### Python

To run the Python sample

1. Change to Python code and install dependancies

```
cd src/python
pip install -r requirements.txt
```

5. Run the app

```
python main.py
```
