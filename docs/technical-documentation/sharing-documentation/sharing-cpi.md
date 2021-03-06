<body>
<div class="container-fluid">
<h1>Thrift module: sharing_cpi</h1>
<table class="table-bordered table-striped table-condensed"><thead><th>Module</th><th>Services</th><th>Data types</th><th>Constants</th></thead>
<tr>
<td>sharing_cpi</td><td><a href="#Svc_SharingRegistryService">SharingRegistryService</a><br/>
<ul>
<li><a href="#Fn_SharingRegistryService_addChildGroupsToParentGroup">addChildGroupsToParentGroup</a></li>
<li><a href="#Fn_SharingRegistryService_addUsersToGroup">addUsersToGroup</a></li>
<li><a href="#Fn_SharingRegistryService_createDomain">createDomain</a></li>
<li><a href="#Fn_SharingRegistryService_createEntity">createEntity</a></li>
<li><a href="#Fn_SharingRegistryService_createEntityType">createEntityType</a></li>
<li><a href="#Fn_SharingRegistryService_createGroup">createGroup</a></li>
<li><a href="#Fn_SharingRegistryService_createPermissionType">createPermissionType</a></li>
<li><a href="#Fn_SharingRegistryService_createUser">createUser</a></li>
<li><a href="#Fn_SharingRegistryService_deleteDomain">deleteDomain</a></li>
<li><a href="#Fn_SharingRegistryService_deleteEntity">deleteEntity</a></li>
<li><a href="#Fn_SharingRegistryService_deleteEntityType">deleteEntityType</a></li>
<li><a href="#Fn_SharingRegistryService_deleteGroup">deleteGroup</a></li>
<li><a href="#Fn_SharingRegistryService_deletePermissionType">deletePermissionType</a></li>
<li><a href="#Fn_SharingRegistryService_deleteUser">deleteUser</a></li>
<li><a href="#Fn_SharingRegistryService_getDomain">getDomain</a></li>
<li><a href="#Fn_SharingRegistryService_getDomains">getDomains</a></li>
<li><a href="#Fn_SharingRegistryService_getEntity">getEntity</a></li>
<li><a href="#Fn_SharingRegistryService_getEntityType">getEntityType</a></li>
<li><a href="#Fn_SharingRegistryService_getEntityTypes">getEntityTypes</a></li>
<li><a href="#Fn_SharingRegistryService_getGroup">getGroup</a></li>
<li><a href="#Fn_SharingRegistryService_getGroupMembersOfTypeGroup">getGroupMembersOfTypeGroup</a></li>
<li><a href="#Fn_SharingRegistryService_getGroupMembersOfTypeUser">getGroupMembersOfTypeUser</a></li>
<li><a href="#Fn_SharingRegistryService_getGroups">getGroups</a></li>
<li><a href="#Fn_SharingRegistryService_getListOfSharedGroups">getListOfSharedGroups</a></li>
<li><a href="#Fn_SharingRegistryService_getListOfSharedUsers">getListOfSharedUsers</a></li>
<li><a href="#Fn_SharingRegistryService_getPermissionType">getPermissionType</a></li>
<li><a href="#Fn_SharingRegistryService_getPermissionTypes">getPermissionTypes</a></li>
<li><a href="#Fn_SharingRegistryService_getUser">getUser</a></li>
<li><a href="#Fn_SharingRegistryService_getUsers">getUsers</a></li>
<li><a href="#Fn_SharingRegistryService_removeChildGroupFromParentGroup">removeChildGroupFromParentGroup</a></li>
<li><a href="#Fn_SharingRegistryService_removeUsersFromGroup">removeUsersFromGroup</a></li>
<li><a href="#Fn_SharingRegistryService_revokeEntitySharingFromGroups">revokeEntitySharingFromGroups</a></li>
<li><a href="#Fn_SharingRegistryService_revokeEntitySharingFromUsers">revokeEntitySharingFromUsers</a></li>
<li><a href="#Fn_SharingRegistryService_searchEntities">searchEntities</a></li>
<li><a href="#Fn_SharingRegistryService_shareEntityWithGroups">shareEntityWithGroups</a></li>
<li><a href="#Fn_SharingRegistryService_shareEntityWithUsers">shareEntityWithUsers</a></li>
<li><a href="#Fn_SharingRegistryService_updateDomain">updateDomain</a></li>
<li><a href="#Fn_SharingRegistryService_updateEntity">updateEntity</a></li>
<li><a href="#Fn_SharingRegistryService_updateEntityType">updateEntityType</a></li>
<li><a href="#Fn_SharingRegistryService_updateGroup">updateGroup</a></li>
<li><a href="#Fn_SharingRegistryService_updatePermissionType">updatePermissionType</a></li>
<li><a href="#Fn_SharingRegistryService_updatedUser">updatedUser</a></li>
<li><a href="#Fn_SharingRegistryService_userHasAccess">userHasAccess</a></li>
</ul>
</td>
<td></td>
<td></code></td>
</tr></table>
<hr/><h2 id="Services">Services</h2>
<h3 id="Svc_SharingRegistryService">Service: SharingRegistryService</h3>
<div class="definition"><h4 id="Fn_SharingRegistryService_createDomain">Function: SharingRegistryService.createDomain</h4>
<pre><code>string</code> createDomain(<code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_Domain">sharing_models.Domain</a></code> domain)
    throws <code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_SharingRegistryException">sharing_models.SharingRegistryException</a></code>
</pre><p>API method to create a new domain</p>
<br/></div><div class="definition"><h4 id="Fn_SharingRegistryService_updateDomain">Function: SharingRegistryService.updateDomain</h4>
<pre><code>bool</code> updateDomain(<code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_Domain">sharing_models.Domain</a></code> domain)
    throws <code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_SharingRegistryException">sharing_models.SharingRegistryException</a></code>
</pre><p>API method to update a domain</p>
<br/></div><div class="definition"><h4 id="Fn_SharingRegistryService_deleteDomain">Function: SharingRegistryService.deleteDomain</h4>
<pre><code>bool</code> deleteDomain(<code>string</code> domainId)
    throws <code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_SharingRegistryException">sharing_models.SharingRegistryException</a></code>
</pre><p>API method to delete domain</p>
<br/></div><div class="definition"><h4 id="Fn_SharingRegistryService_getDomain">Function: SharingRegistryService.getDomain</h4>
<pre><code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_Domain">sharing_models.Domain</a></code> getDomain(<code>string</code> domainId)
    throws <code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_SharingRegistryException">sharing_models.SharingRegistryException</a></code>
</pre><p>API method to retrieve a domain</p>
<br/></div><div class="definition"><h4 id="Fn_SharingRegistryService_getDomains">Function: SharingRegistryService.getDomains</h4>
<pre><code>list&lt;<code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_Domain">sharing_models.Domain</a></code>&gt;</code> getDomains(<code>i32</code> offset,
                                       <code>i32</code> limit)
    throws <code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_SharingRegistryException">sharing_models.SharingRegistryException</a></code>
</pre><p>API method to get all domain.</p>
<br/></div><div class="definition"><h4 id="Fn_SharingRegistryService_createUser">Function: SharingRegistryService.createUser</h4>
<pre><code>string</code> createUser(<code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_User">sharing_models.User</a></code> user)
    throws <code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_SharingRegistryException">sharing_models.SharingRegistryException</a></code>
</pre><p>API method to register a user in the system</p>
<br/></div><div class="definition"><h4 id="Fn_SharingRegistryService_updatedUser">Function: SharingRegistryService.updatedUser</h4>
<pre><code>bool</code> updatedUser(<code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_User">sharing_models.User</a></code> user)
    throws <code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_SharingRegistryException">sharing_models.SharingRegistryException</a></code>
</pre><p>API method to update existing user</p>
<br/></div><div class="definition"><h4 id="Fn_SharingRegistryService_deleteUser">Function: SharingRegistryService.deleteUser</h4>
<pre><code>bool</code> deleteUser(<code>string</code> domainId,
                <code>string</code> userId)
    throws <code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_SharingRegistryException">sharing_models.SharingRegistryException</a></code>
</pre><p>API method to delete user</p>
<br/></div><div class="definition"><h4 id="Fn_SharingRegistryService_getUser">Function: SharingRegistryService.getUser</h4>
<pre><code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_User">sharing_models.User</a></code> getUser(<code>string</code> domainId,
                            <code>string</code> userId)
    throws <code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_SharingRegistryException">sharing_models.SharingRegistryException</a></code>
</pre><p>API method to get a user</p>
<br/></div><div class="definition"><h4 id="Fn_SharingRegistryService_getUsers">Function: SharingRegistryService.getUsers</h4>
<pre><code>list&lt;<code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_User">sharing_models.User</a></code>&gt;</code> getUsers(<code>string</code> domainId,
                                   <code>i32</code> offset,
                                   <code>i32</code> limit)
    throws <code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_SharingRegistryException">sharing_models.SharingRegistryException</a></code>
</pre><p>API method to get a list of users in a specific domain.</p>
<li>domainId : Domain id</li>
<li>offset : Starting result number</li>
<li>limit : Number of max results to be sent</li>
<br/></div><div class="definition"><h4 id="Fn_SharingRegistryService_createGroup">Function: SharingRegistryService.createGroup</h4>
<pre><code>string</code> createGroup(<code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_UserGroup">sharing_models.UserGroup</a></code> group)
    throws <code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_SharingRegistryException">sharing_models.SharingRegistryException</a></code>
</pre><p>API method to create a new group</p>
<br/></div><div class="definition"><h4 id="Fn_SharingRegistryService_updateGroup">Function: SharingRegistryService.updateGroup</h4>
<pre><code>bool</code> updateGroup(<code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_UserGroup">sharing_models.UserGroup</a></code> group)
    throws <code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_SharingRegistryException">sharing_models.SharingRegistryException</a></code>
</pre><p>API method to update a group</p>
<br/></div><div class="definition"><h4 id="Fn_SharingRegistryService_deleteGroup">Function: SharingRegistryService.deleteGroup</h4>
<pre><code>bool</code> deleteGroup(<code>string</code> domainId,
                 <code>string</code> groupId)
    throws <code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_SharingRegistryException">sharing_models.SharingRegistryException</a></code>
</pre><p>API method to delete a group</p>
<br/></div><div class="definition"><h4 id="Fn_SharingRegistryService_getGroup">Function: SharingRegistryService.getGroup</h4>
<pre><code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_UserGroup">sharing_models.UserGroup</a></code> getGroup(<code>string</code> domainId,
                                  <code>string</code> groupId)
    throws <code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_SharingRegistryException">sharing_models.SharingRegistryException</a></code>
</pre><p>API method to get a group</p>
<br/></div><div class="definition"><h4 id="Fn_SharingRegistryService_getGroups">Function: SharingRegistryService.getGroups</h4>
<pre><code>list&lt;<code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_UserGroup">sharing_models.UserGroup</a></code>&gt;</code> getGroups(<code>string</code> domainId,
                                         <code>i32</code> offset,
                                         <code>i32</code> limit)
</pre><p>API method to get groups in a domainId.</p>
<br/></div><div class="definition"><h4 id="Fn_SharingRegistryService_addUsersToGroup">Function: SharingRegistryService.addUsersToGroup</h4>
<pre><code>bool</code> addUsersToGroup(<code>string</code> domainId,
                     <code>list&lt;<code>string</code>&gt;</code> userIds,
                     <code>string</code> groupId)
    throws <code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_SharingRegistryException">sharing_models.SharingRegistryException</a></code>
</pre><p>API method to add list of users to a group</p>
<br/></div><div class="definition"><h4 id="Fn_SharingRegistryService_removeUsersFromGroup">Function: SharingRegistryService.removeUsersFromGroup</h4>
<pre><code>bool</code> removeUsersFromGroup(<code>string</code> domainId,
                          <code>list&lt;<code>string</code>&gt;</code> userIds,
                          <code>string</code> groupId)
    throws <code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_SharingRegistryException">sharing_models.SharingRegistryException</a></code>
</pre><p>API method to remove users from a group</p>
<br/></div><div class="definition"><h4 id="Fn_SharingRegistryService_getGroupMembersOfTypeUser">Function: SharingRegistryService.getGroupMembersOfTypeUser</h4>
<pre><code>list&lt;<code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_User">sharing_models.User</a></code>&gt;</code> getGroupMembersOfTypeUser(<code>string</code> domainId,
                                                    <code>string</code> groupId,
                                                    <code>i32</code> offset,
                                                    <code>i32</code> limit)
    throws <code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_SharingRegistryException">sharing_models.SharingRegistryException</a></code>
</pre><p>API method to get list of child users in a group. Only the direct members will be returned.</p>
<br/></div><div class="definition"><h4 id="Fn_SharingRegistryService_getGroupMembersOfTypeGroup">Function: SharingRegistryService.getGroupMembersOfTypeGroup</h4>
<pre><code>list&lt;<code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_UserGroup">sharing_models.UserGroup</a></code>&gt;</code> getGroupMembersOfTypeGroup(<code>string</code> domainId,
                                                          <code>string</code> groupId,
                                                          <code>i32</code> offset,
                                                          <code>i32</code> limit)
    throws <code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_SharingRegistryException">sharing_models.SharingRegistryException</a></code>
</pre><p>API method to get list of child groups in a group. Only the direct members will be returned.</p>
<br/></div><div class="definition"><h4 id="Fn_SharingRegistryService_addChildGroupsToParentGroup">Function: SharingRegistryService.addChildGroupsToParentGroup</h4>
<pre><code>bool</code> addChildGroupsToParentGroup(<code>string</code> domainId,
                                 <code>list&lt;<code>string</code>&gt;</code> childIds,
                                 <code>string</code> groupId)
    throws <code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_SharingRegistryException">sharing_models.SharingRegistryException</a></code>
</pre><p>API method to add a child group to a parent group.</p>
<br/></div><div class="definition"><h4 id="Fn_SharingRegistryService_removeChildGroupFromParentGroup">Function: SharingRegistryService.removeChildGroupFromParentGroup</h4>
<pre><code>bool</code> removeChildGroupFromParentGroup(<code>string</code> domainId,
                                     <code>string</code> childId,
                                     <code>string</code> groupId)
    throws <code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_SharingRegistryException">sharing_models.SharingRegistryException</a></code>
</pre><p>API method to remove a child group from parent group.</p>
<br/></div><div class="definition"><h4 id="Fn_SharingRegistryService_createEntityType">Function: SharingRegistryService.createEntityType</h4>
<pre><code>string</code> createEntityType(<code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_EntityType">sharing_models.EntityType</a></code> entityType)
    throws <code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_SharingRegistryException">sharing_models.SharingRegistryException</a></code>
</pre><p>API method to create a new entity type</p>
<br/></div><div class="definition"><h4 id="Fn_SharingRegistryService_updateEntityType">Function: SharingRegistryService.updateEntityType</h4>
<pre><code>bool</code> updateEntityType(<code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_EntityType">sharing_models.EntityType</a></code> entityType)
    throws <code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_SharingRegistryException">sharing_models.SharingRegistryException</a></code>
</pre><p>API method to update entity type</p>
<br/></div><div class="definition"><h4 id="Fn_SharingRegistryService_deleteEntityType">Function: SharingRegistryService.deleteEntityType</h4>
<pre><code>bool</code> deleteEntityType(<code>string</code> domainId,
                      <code>string</code> entityTypeId)
    throws <code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_SharingRegistryException">sharing_models.SharingRegistryException</a></code>
</pre><p>API method to delete entity type</p>
<br/></div><div class="definition"><h4 id="Fn_SharingRegistryService_getEntityType">Function: SharingRegistryService.getEntityType</h4>
<pre><code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_EntityType">sharing_models.EntityType</a></code> getEntityType(<code>string</code> domainId,
                                        <code>string</code> entityTypeId)
    throws <code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_SharingRegistryException">sharing_models.SharingRegistryException</a></code>
</pre><p>API method to get an entity type</p>
<br/></div><div class="definition"><h4 id="Fn_SharingRegistryService_getEntityTypes">Function: SharingRegistryService.getEntityTypes</h4>
<pre><code>list&lt;<code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_EntityType">sharing_models.EntityType</a></code>&gt;</code> getEntityTypes(<code>string</code> domainId,
                                               <code>i32</code> offset,
                                               <code>i32</code> limit)
    throws <code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_SharingRegistryException">sharing_models.SharingRegistryException</a></code>
</pre><p>API method to get entity types in a domainId.</p>
<br/></div><div class="definition"><h4 id="Fn_SharingRegistryService_createEntity">Function: SharingRegistryService.createEntity</h4>
<pre><code>string</code> createEntity(<code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_Entity">sharing_models.Entity</a></code> entity)
    throws <code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_SharingRegistryException">sharing_models.SharingRegistryException</a></code>
</pre><p>API method to register new entity</p>
<br/></div><div class="definition"><h4 id="Fn_SharingRegistryService_updateEntity">Function: SharingRegistryService.updateEntity</h4>
<pre><code>bool</code> updateEntity(<code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_Entity">sharing_models.Entity</a></code> entity)
    throws <code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_SharingRegistryException">sharing_models.SharingRegistryException</a></code>
</pre><p>API method to update entity</p>
<br/></div><div class="definition"><h4 id="Fn_SharingRegistryService_deleteEntity">Function: SharingRegistryService.deleteEntity</h4>
<pre><code>bool</code> deleteEntity(<code>string</code> domainId,
                  <code>string</code> entityId)
    throws <code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_SharingRegistryException">sharing_models.SharingRegistryException</a></code>
</pre><p>API method to delete entity</p>
<br/></div><div class="definition"><h4 id="Fn_SharingRegistryService_getEntity">Function: SharingRegistryService.getEntity</h4>
<pre><code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_Entity">sharing_models.Entity</a></code> getEntity(<code>string</code> domainId,
                                <code>string</code> entityId)
    throws <code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_SharingRegistryException">sharing_models.SharingRegistryException</a></code>
</pre><p>API method to get entity</p>
<br/></div><div class="definition"><h4 id="Fn_SharingRegistryService_searchEntities">Function: SharingRegistryService.searchEntities</h4>
<pre><code>list&lt;<code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_Entity">sharing_models.Entity</a></code>&gt;</code> searchEntities(<code>string</code> domainId,
                                           <code>string</code> userId,
                                           <code>list&lt;<code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_SearchCriteria">sharing_models.SearchCriteria</a></code>&gt;</code> filters,
                                           <code>i32</code> offset,
                                           <code>i32</code> limit)
    throws <code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_SharingRegistryException">sharing_models.SharingRegistryException</a></code>
</pre><p>API method to search entities</p>
<br/></div><div class="definition"><h4 id="Fn_SharingRegistryService_getListOfSharedUsers">Function: SharingRegistryService.getListOfSharedUsers</h4>
<pre><code>list&lt;<code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_User">sharing_models.User</a></code>&gt;</code> getListOfSharedUsers(<code>string</code> domainId,
                                               <code>string</code> entityId,
                                               <code>string</code> permissionTypeId)
    throws <code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_SharingRegistryException">sharing_models.SharingRegistryException</a></code>
</pre><p>API method to get a list of shared users given the entity id</p>
<br/></div><div class="definition"><h4 id="Fn_SharingRegistryService_getListOfSharedGroups">Function: SharingRegistryService.getListOfSharedGroups</h4>
<pre><code>list&lt;<code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_UserGroup">sharing_models.UserGroup</a></code>&gt;</code> getListOfSharedGroups(<code>string</code> domainId,
                                                     <code>string</code> entityId,
                                                     <code>string</code> permissionTypeId)
    throws <code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_SharingRegistryException">sharing_models.SharingRegistryException</a></code>
</pre><p>API method to get a list of shared groups given the entity id</p>
<br/></div><div class="definition"><h4 id="Fn_SharingRegistryService_createPermissionType">Function: SharingRegistryService.createPermissionType</h4>
<pre><code>string</code> createPermissionType(<code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_PermissionType">sharing_models.PermissionType</a></code> permissionType)
    throws <code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_SharingRegistryException">sharing_models.SharingRegistryException</a></code>
</pre><p>API method to create permission type</p>
<br/></div><div class="definition"><h4 id="Fn_SharingRegistryService_updatePermissionType">Function: SharingRegistryService.updatePermissionType</h4>
<pre><code>bool</code> updatePermissionType(<code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_PermissionType">sharing_models.PermissionType</a></code> permissionType)
    throws <code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_SharingRegistryException">sharing_models.SharingRegistryException</a></code>
</pre><p>API method to update permission type</p>
<br/></div><div class="definition"><h4 id="Fn_SharingRegistryService_deletePermissionType">Function: SharingRegistryService.deletePermissionType</h4>
<pre><code>bool</code> deletePermissionType(<code>string</code> domainId,
                          <code>string</code> permissionTypeId)
    throws <code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_SharingRegistryException">sharing_models.SharingRegistryException</a></code>
</pre><p>API method to delete permission type</p>
<br/></div><div class="definition"><h4 id="Fn_SharingRegistryService_getPermissionType">Function: SharingRegistryService.getPermissionType</h4>
<pre><code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_PermissionType">sharing_models.PermissionType</a></code> getPermissionType(<code>string</code> domainId,
                                                <code>string</code> permissionTypeId)
    throws <code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_SharingRegistryException">sharing_models.SharingRegistryException</a></code>
</pre><p>API method to get permission type</p>
<br/></div><div class="definition"><h4 id="Fn_SharingRegistryService_getPermissionTypes">Function: SharingRegistryService.getPermissionTypes</h4>
<pre><code>list&lt;<code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_PermissionType">sharing_models.PermissionType</a></code>&gt;</code> getPermissionTypes(<code>string</code> domainId,
                                                       <code>i32</code> offset,
                                                       <code>i32</code> limit)
    throws <code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_SharingRegistryException">sharing_models.SharingRegistryException</a></code>
</pre><p>API method to get list of permission types in a given domainId.</p>
<br/></div><div class="definition"><h4 id="Fn_SharingRegistryService_shareEntityWithUsers">Function: SharingRegistryService.shareEntityWithUsers</h4>
<pre><code>bool</code> shareEntityWithUsers(<code>string</code> domainId,
                          <code>string</code> entityId,
                          <code>list&lt;<code>string</code>&gt;</code> userList,
                          <code>string</code> perssionTypeId,
                          <code>bool</code> cascadePermission)
    throws <code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_SharingRegistryException">sharing_models.SharingRegistryException</a></code>
</pre><p>API method to share an entity with users</p>
<br/></div><div class="definition"><h4 id="Fn_SharingRegistryService_revokeEntitySharingFromUsers">Function: SharingRegistryService.revokeEntitySharingFromUsers</h4>
<pre><code>bool</code> revokeEntitySharingFromUsers(<code>string</code> domainId,
                                  <code>string</code> entityId,
                                  <code>list&lt;<code>string</code>&gt;</code> userList,
                                  <code>string</code> perssionTypeId)
    throws <code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_SharingRegistryException">sharing_models.SharingRegistryException</a></code>
</pre><p>API method to revoke sharing from a list of users</p>
<br/></div><div class="definition"><h4 id="Fn_SharingRegistryService_shareEntityWithGroups">Function: SharingRegistryService.shareEntityWithGroups</h4>
<pre><code>bool</code> shareEntityWithGroups(<code>string</code> domainId,
                           <code>string</code> entityId,
                           <code>list&lt;<code>string</code>&gt;</code> groupList,
                           <code>string</code> perssionTypeId,
                           <code>bool</code> cascadePermission)
    throws <code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_SharingRegistryException">sharing_models.SharingRegistryException</a></code>
</pre><p>API method to share an entity with list of groups</p>
<br/></div><div class="definition"><h4 id="Fn_SharingRegistryService_revokeEntitySharingFromGroups">Function: SharingRegistryService.revokeEntitySharingFromGroups</h4>
<pre><code>bool</code> revokeEntitySharingFromGroups(<code>string</code> domainId,
                                   <code>string</code> entityId,
                                   <code>list&lt;<code>string</code>&gt;</code> groupList,
                                   <code>string</code> perssionTypeId)
    throws <code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_SharingRegistryException">sharing_models.SharingRegistryException</a></code>
</pre><p>API method to revoke sharing from list of users</p>
<br/></div><div class="definition"><h4 id="Fn_SharingRegistryService_userHasAccess">Function: SharingRegistryService.userHasAccess</h4>
<pre><code>bool</code> userHasAccess(<code>string</code> domainId,
                   <code>string</code> userId,
                   <code>string</code> entityId,
                   <code>string</code> permissionTypeId)
    throws <code><a href="/technical-documentation/sharing-documentation/sharing-models/#Struct_SharingRegistryException">sharing_models.SharingRegistryException</a></code>
</pre><p>API method to check whether a user has access to a specific entity</p>
<br/></div></div></body></html>
