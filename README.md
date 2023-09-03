# cobratest

## ERROR BUILDING
```
➜  aa git:(main) go build .        
# github.com/khanakia/cobratest
/usr/local/go/pkg/tool/darwin_arm64/link: running clang failed: exit status 1
Undefined symbols for architecture arm64:
  "_darwin_arm_init_mach_exception_handler", referenced from:
      _x_cgo_init in 000005.o
  "_darwin_arm_init_thread_exception_port", referenced from:
      _threadentry in 000005.o
      _x_cgo_init in 000005.o
ld: symbol(s) not found for architecture arm64
clang: error: linker command failed with exit code 1 (use -v to see invocation)

```

## GO ENV
```
➜  aa git:(main) go env    
GO111MODULE=''
GOARCH='arm64'
GOBIN=''
GOCACHE='/Users/demo/Library/Caches/go-build'
GOENV='/Users/demo/Library/Application Support/go/env'
GOEXE=''
GOEXPERIMENT=''
GOFLAGS=''
GOHOSTARCH='arm64'
GOHOSTOS='darwin'
GOINSECURE=''
GOMODCACHE='/Users/demo/go/pkg/mod'
GONOPROXY=''
GONOSUMDB=''
GOOS='darwin'
GOPATH='/Users/demo/go'
GOPRIVATE=''
GOPROXY='https://proxy.golang.org,direct'
GOROOT='/usr/local/go'
GOSUMDB='sum.golang.org'
GOTMPDIR=''
GOTOOLCHAIN='auto'
GOTOOLDIR='/usr/local/go/pkg/tool/darwin_arm64'
GOVCS=''
GOVERSION='go1.21.0'
GCCGO='gccgo'
AR='ar'
CC='clang'
CXX='clang++'
CGO_ENABLED='1'
GOMOD='/Users/demo/Downloads/aa/go.mod'
GOWORK=''
CGO_CFLAGS='-O2 -g'
CGO_CPPFLAGS=''
CGO_CXXFLAGS='-O2 -g'
CGO_FFLAGS='-O2 -g'
CGO_LDFLAGS='-O2 -g'
PKG_CONFIG='pkg-config'
GOGCCFLAGS='-fPIC -arch arm64 -pthread -fno-caret-diagnostics -Qunused-arguments -fmessage-length=0 -ffile-prefix-map=/var/folders/qk/jzsg52995wn53dv8bw62dl1w0000gn/T/go-build3833455105=/tmp/go-build -gno-record-gcc-switches -fno-common'
```
