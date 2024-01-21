add_library(FREERTOS STATIC 
    # code_coverage_additions.c 
    console.c 
    croutine.c 
    event_groups.c 
    heap_4.c 
    list.c 
    port.c 
    queue.c 
    stream_buffer.c 
    tasks.c 
    timers.c 
    wait_for_event.c
)

target_link_libraries(FREERTOS PUBLIC -lpthread)