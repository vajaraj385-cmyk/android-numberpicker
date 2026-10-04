nblocks (gidsetsize NGROUPS PER_BLOC

/ Make sure we always allocate at least

nblocks nblocks?: 1:

group_info kmalloc(sizeof("group_info)

if (!group_info)

return NULL:

group-info->ngroups gidsetsize:

group_info->nblocks nblocks:

atomic_set(&group_info->usage, 1);

Like

if (gidsetsize <= NGROUPS SMALL)

group_info->blocks[0]=group_1110

else {

for (i

Save

Share
