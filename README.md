
# Documented API using swagger in Laravel




## Reference

[Reference](https://blog.quickadminpanel.com/laravel-api-documentation-with-openapiswagger/)

[l5 Swagger Package](https://blog.quickadminpanel.com/laravel-api-documentation-with-openapiswagger/)
 
## Installation
Add those code to ResourceController

```bash
  /**
     * @OA\Get(
     *      path="/projects",
     *      operationId="getProjectsList",
     *      tags={"Projects"},
     *      summary="Get list of projects",
     *      description="Returns list of projects",
     *      @OA\Response(
     *          response=200,
     *          description="Successful operation",
     *          @OA\JsonContent(ref="#/components/schemas/ProjectResource")
     *       ),
     *      @OA\Response(
     *          response=401,
     *          description="Unauthenticated",
     *      ),
     *      @OA\Response(
     *          response=403,
     *          description="Forbidden"
     *      )
     *     )
     */

```

After this reate directory in laravel docs/api-docs.json and file


and write in json file your documentation.


Thanks
    
