# Flet-Native 🚀

**Flet-Native** is a cutting-edge tool designed to simplify the compilation of **non-pure Python** packages, which may include components written in languages like C, C++, or Rust. 🛠️

## Key Features 🌟

- **Easy Integration**: Compile popular packages like `firebase-admin` for iOS and Android with minimal effort.
- **Automated Workflow**: Just add your required libraries to the `requirements.txt` file, and Flet-Native handles the rest! 🔄
- **No Hacks or Patches**: Say goodbye to complex workarounds; our tool streamlines the process for you. 🙌

## Usage 📦
1.To see a dependency graph for a package you can use
```plaintext
pipgrip firebase_admin
```
2. Add your non-pure Python package requirements to the `requirements.txt` file with dependency if exist.   
3. Run the workflow to automate the compilation process.

### Example `requirements.txt`:

```plaintext
firebase-admin
cachecontrol
msgpack
requests
certifi
charset-normalizer
idna
urllib3
google-api-core
google-auth
cachetools
pyasn1-modules
pyasn1
rsa
googleapis-common-protos
protobuf
grpcio-status
grpcio
proto-plus
google-api-python-client
google-auth-httplib2
httplib2
pyparsing
uritemplate
google-cloud-firestore
google-cloud-core
google-cloud-storage
google-crc32c
google-resumable-media
pyjwt
cryptography
cffi
pycparser
