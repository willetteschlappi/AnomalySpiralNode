# AnomalySpiralNode

AnomalySpiralNode recursively scans event structures and execution flows for nested anomalies and pattern escapes in layered systems like containers, VMs, or distributed runtimes.

## Features
- Recursive event tracing (parent → child → leaf).
- Anomaly scoring based on depth and deviation.
- Radial visualization of deviation nodes.
- Works with JSONL audit logs or structured flows.

## Usage
```bash
git clone https://github.com/your-org/AnomalySpiralNode.git
cd AnomalySpiralNode
python spiralnode/observer.py logs/nested_audit.jsonl
