bump_sources = [
    'bump-async-priority-queue.vala',
    'bump-callback-queue.vala',
    'bump-claim.vala',
    'bump-event.vala',
    'bump-factory.vala',
    'bump-lazy.vala',
    'bump-queue.vala',
    'bump-resource-claim.vala',
    'bump-resource-pool.vala',
    'bump-semaphore-claim.vala',
    'bump-semaphore.vala',
    'bump-task-queue.vala',
    'bump-threading.vala',
    'bump-worker.vala']
bump_lib = library('bump', bump_sources,
                   dependencies: [glib_dep, gobject_dep, gio_dep, gee_dep])

bump_dep = declare_dependency(include_directories: include_directories('.'),
                              link_with: bump_lib,
                              dependencies: [gee_dep])
