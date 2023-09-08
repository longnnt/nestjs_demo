# nestjs_demo
## Issue:
1.
- Dto don't show in swagger schemas because using @Query, @Param.
- Fix:
   - Using @Body decorator.
   - Or using @ApiExtraModel()
   - ![image](https://github.com/longnnt/nestjs_demo/assets/47670554/20578548-72db-45b4-8fe5-7c8d0e5b496d)
   - [Link git] (https://github.com/nestjs/swagger/issues/954)

