all: sfgpufd3d

sfgpufd3d: Mgpufd3d.cu
	nvcc -o sfgpufd3d Mgpufd3d.cu -I/usr/local/madagascar-1.6.4/include -lm -L/usr/local/madagacar-1.6.4/lib 

clean:
	rm -f sfgpufd3d


