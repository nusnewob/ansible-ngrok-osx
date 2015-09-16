# ansible-ngrok-osx

## Requirement

```
brew
```

## Usage

Specify your ngrok API key, your client meta name and list of tunnels

```
  vars:
    ngrok_api_key: your_ngrok_api_key
    ngrok_client_name: your_machine_identifier
    ngrok_tunnels:
      vnc:
        proto: tcp
        addr: 5900
      ssh:
        proto: tcp
        addr: 22
```
