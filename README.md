# nestjs_demo
## Issue:
1. DTO
- Dto don't show in swagger schemas because using @Query, @Param.
- Fix:
   - Using @Body decorator.
   - Or using @ApiExtraModel()
   - ![image](https://github.com/longnnt/nestjs_demo/assets/47670554/20578548-72db-45b4-8fe5-7c8d0e5b496d)
   - [Link git] (https://github.com/nestjs/swagger/issues/954)

2. Public route ( Don't need authorization to get data )
- Make custom decorator\
  ![image](https://github.com/longnnt/nestjs_demo/assets/47670554/fb6db9da-4957-491f-9b18-55a766c440c2)
- 'isPublic' is metadata key, 'true' is metadata value\
  ![image](https://github.com/longnnt/nestjs_demo/assets/47670554/9ccb678e-3992-4675-86e7-2e4cde4e6edb)

