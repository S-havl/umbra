CFLAGS = -std=c++17 -O2
LDFLAGS = -lglfw -lvulkan -ldl -lpthread -lX11 -lXxf86vm -lXrandr -lXi

TriangleVulkanTest: main.cpp
	g++ $(CFLAGS) -o TriangleVulkanTest main.cpp $(LDFLAGS) 

.PHONY: test clean

test: TriangleVulkanTest
	./TriangleVulkanTest

clean:
	rm -rf TriangleVulkanTest
