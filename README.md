# zig-wasm-test

A minimal Web Assembly example built from Zig's init-lib.

## Install Zig

	curl -sS https://webi.sh/zig | sh

## Building

	zig build

You need to move the resulting wasmtest.wasm file from /zig-cache/ to /www/


## Running

	cd www
	npm start
