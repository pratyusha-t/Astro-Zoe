IPC_DIR = /home/satish/ipc-3.9.1#Path to IPC root directory

IPC_INCLUDE = "${IPC_DIR}/include"
IPC_LIB = "${IPC_DIR}/lib/Linux-3.8" #Linux version need to be updated

CFLAGS = -I${IPC_INCLUDE}
LFLAGS = -L${IPC_LIB} -lipc

all: ZoeMotionSim.c
	gcc ZoeMotionSim.c -o ZoeMotionSim ${CFLAGS} ${LFLAGS}

clean:
	rm ZoeMotionSim
