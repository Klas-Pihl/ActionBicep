# ActionBicep
Hard workout

## Plan
Deploy a Azure resource by ARM tamplate generated by Bicep in GitHub action.

### Register Azure SP in GitHub

### Write Bicep

### Run Bicep and deploy code
#### Install Bicep in worker
##### Install the Bicep CLI

###### Linux
```sh
# Fetch the latest Bicep CLI binary
curl -Lo bicep https://github.com/Azure/bicep/releases/latest/download/bicep-linux-x64
# Mark it as executable
chmod +x ./bicep
# Add bicep to your PATH (requires admin)
sudo mv ./bicep /usr/local/bin/bicep
# Verify you can now access the 'bicep' command
bicep --help
# Done!

```

