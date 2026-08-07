#!/usr/bin/env bash
set -euo pipefail

# Make script executable when checked out (Git may not preserve exec bit via API),
# but GitHub will store file contents as-is. This file is intended to be run on a runner.
