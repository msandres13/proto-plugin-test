# proto-plugin-test
<pre>
Debug project for clion
proto internal includes not resolved
I am using a container to compile and run with the following rpm list
rpmlint rpm-build findutils passwd tar rsync git which make cmake-3.11.4 clang gdb gcc gcc-c++ dbus-devel openssl-devel grpc grpc-plugins grpc-devel protobuf protobuf-devel python3 python3-devel openssh-server gtest-devel gmock-devel systemd-devel logging-client-cpp-devel zfw-trace-devel valgrind
The container is started using the jetbrains recommended settings.
podman run --rm -it --cap-add AUDIT_WRITE --cap-add sys_ptrace p 127.0.0.1:2222:2222 build-container
</pre>
