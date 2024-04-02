Build and run test
==================
	git submodule update --init --recursive
	mkdir -p build
	cd build
	cmake -Dgtest_force_shared_crt=ON ..      
	cmake --build .
	ctest -C Debug -V
                
