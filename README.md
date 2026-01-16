"https://mprosit.axismaxlife.com/api/transformerservice/createlead
Caused by: org.springframework.dao.IncorrectResultSizeDataAccessException: Query { "$java" : Query: { "constitutionCode" : "1", "constitutionStatus" : { "$regularExpression" : { "pattern" : "^YES$", "options" : "i"}}}, Fields: {}, Sort: {} } returned non unique result

https://mprodevms.maxlifeinsurance.com/api/transformerservice/createlead


Received request at createlead with body


Response from external API


Processed request in {} ms


Processed request in ms For CreateLead :{}


Request For ProcessLandingRecord at



2026-01-16 15:29:25 4084d940-cbdc-49eb-9606-51ea4a658894  matrix-sit-transformer-hub-fargate-container [http-nio-8080-exec-3]INFO  c.m.m.s.i.AxisLeadTransformationServiceImpl - Request For ProcessLandingRecord at : ThanosHookInsertLandingDTO{crmId=585117500317, customerId='NTE2OTY3OTc5', agentId='618359', insertDate=Fri Jan 16 15:29:25 UTC 2026, agentName='Preetam', agentEmailId='LGemailID@JK.COM', agentPhoneNo='789898989', agentRole='ASM', customerTitle='mr', firstName='UDIT ', middleName='', surName='Kumar', dob=Fri May 09 00:00:00 UTC 1986, gender='M', pan='AJFPV8829C', mobileNumber='9650989475', emailAddress='uditkumar@gmail.com', stdOffice='', telNo='', stdOffice1='', telNo1='', ckycNo='50022770388857', address1='11/6,NETHAJI NAGAR,KULATHUPALAYAM,COIMBATORE', address2=' -', city='COIMBATORE', state='tamil_nadu', country='India', pinCode='641109', permanentAddress1='90 a', permanentAddress2='AH Street', city1='JALANDHAR', state1='', country1='INDIA', pinCode1='144001', branchCode='0012', branchName='HADAPSAR PUNE', customerSegment='PRIME', schemeCode='SBNRE', constitutionCode='01', kycStatus='12', omniFlowLink=1, crmStatus=5, accountNo='13132434554', accountType='SBA', ifscCode='UTIB0000404', accountOpeningDate=Wed Mar 01 00:00:00 UTC 2000, offerId=401, offerName='PASAR11', ukycFlag='Y', spCode='SP0069520143', additionalData=AdditionalDataDTO [isNumberIndian=Y, isLIEqualsPH=Y, dobOfInsured=, education=Graduate, occupation=Salaried, hasExistingLICover=N, existingLICover=, leadSourceOption=, insuredFirstName=, insuredMiddleName=, insuredLastName=, insuredGender=, relationWithProposer=], psmDetails=PSMDetailsRequestDTO [productType=Non-POS, isRecommendedProduct=Y, isSolution=N, recommendedProducts=[Max Life Saral Jeevan Bima, Max Life Cancer Insurance Plan, Forever Young Pension Plan, Max Life Life Perfect Partner Super, Max Life Fast Track Super Plan, Max Life Monthly Income Advantage Plan, Max Life Platinum Wealth Plan, Max Life Future Genius Education Plan, Max Life Savings Advantage Plan, Max Life Flexi Wealth Plus Plan, Max Life Smart Wealth Plan, Max Life Saral Pension Plan, Max Life Smart Secure Plus Plan, Max Life Smart Wealth Income Plan, Max Life Flexi Wealth Plus Plan, Max Life Smart Wealth Advantage guarantee Plan], selectedProduct=133, selectedProductName=Max Life Smart Wealth Pla, income=1000000, lifeStage=1, goalSelected=protection, riskAppetite=Medium]}





Jan 16, 2026 @ 20:59:26.074


	at org.springframework.data.repository.core.support.QueryExecutorMethodInterceptor.invoke(QueryExecutorMethodInterceptor.java:149)


	Jan 16, 2026 @ 20:59:26.074


	at org.springframework.aop.framework.ReflectiveMethodInvocation.proceed(ReflectiveMethodInvocation.java:184)


	Jan 16, 2026 @ 20:59:26.074


	at org.springframework.data.projection.DefaultMethodInvokingMethodInterceptor.invoke(DefaultMethodInvokingMethodInterceptor.java:69)


	Jan 16, 2026 @ 20:59:26.074


	at org.springframework.aop.framework.ReflectiveMethodInvocation.proceed(ReflectiveMethodInvocation.java:184)


	Jan 16, 2026 @ 20:59:26.074


	at org.springframework.data.mongodb.repository.support.CrudMethodMetadataPostProcessor$CrudMethodMetadataPopulatingMethodInterceptor.invoke(CrudMethodMetadataPostProcessor.java:129)


	Jan 16, 2026 @ 20:59:26.074


	at org.springframework.aop.framework.ReflectiveMethodInvocation.proceed(ReflectiveMethodInvocation.java:184)


	Jan 16, 2026 @ 20:59:26.074


	at org.springframework.aop.framework.JdkDynamicAopProxy.invoke(JdkDynamicAopProxy.java:223)


	Jan 16, 2026 @ 20:59:26.074


	at jdk.proxy2/jdk.proxy2.$Proxy118.findByAxisCountryDef(Unknown Source)


	Jan 16, 2026 @ 20:59:26.074


	at com.mli.mpro.service.impl.AxisLeadTransformationServiceImpl.findMsalesCountryByAxisCountryDef(AxisLeadTransformationServiceImpl.java:627)


	Jan 16, 2026 @ 20:59:26.074


	at com.mli.mpro.service.impl.AxisLeadTransformationServiceImpl.performLookupsAndTransformations(AxisLeadTransformationServiceImpl.java:272)


	Jan 16, 2026 @ 20:59:26.074


	at com.mli.mpro.service.impl.AxisLeadTransformationServiceImpl.processLandingRecord(AxisLeadTransformationServiceImpl.java:74)


	Jan 16, 2026 @ 20:59:26.074


	... 61 common frames omitted


	Jan 16, 2026 @ 20:59:26.074


2026-01-16 15:29:26 4084d940-cbdc-49eb-9606-51ea4a658894  matrix-sit-transformer-hub-fargate-container [http-nio-8080-exec-3]INFO  c.m.m.s.impl.IntegrationServiceImpl - pushToMPro completed successfully for CRM ID: 585117500317, Status: Failure


	Jan 16, 2026 @ 20:59:26.073


2026-01-16 15:29:26 4084d940-cbdc-49eb-9606-51ea4a658894  matrix-sit-transformer-hub-fargate-container [http-nio-8080-exec-3]ERROR c.m.m.s.impl.IntegrationServiceImpl - CRM ID - 585117500317 - Error while mapping or saving data to AxisHookInsertLanding table - 


	Jan 16, 2026 @ 20:59:26.073


java.lang.Exception: Error processing landing record


	Jan 16, 2026 @ 20:59:26.073


	at com.mli.mpro.service.impl.AxisLeadTransformationServiceImpl.processLandingRecord(AxisLeadTransformationServiceImpl.java:107)


	Jan 16, 2026 @ 20:59:26.073


	at com.mli.mpro.service.impl.IntegrationServiceImpl.pushToMPro(IntegrationServiceImpl.java:134)


	Jan 16, 2026 @ 20:59:26.073


	at com.mli.mpro.service.impl.IntegrationServiceImpl.pushToMproWrapper(IntegrationServiceImpl.java:966)


	Jan 16, 2026 @ 20:59:26.073


	at com.mli.mpro.service.impl.J3TeleBindingTransformationServiceImpl.processJourney(J3TeleBindingTransformationServiceImpl.java:122)


	Jan 16, 2026 @ 20:59:26.073


	at com.mli.mpro.util.J3TeleBTestEnvironmentAPI.callPushDataService(J3TeleBTestEnvironmentAPI.java:113)


	Jan 16, 2026 @ 20:59:26.073


	at com.mli.mpro.util.J3TeleBTestEnvironmentAPI.createLead(J3TeleBTestEnvironmentAPI.java:51)


	Jan 16, 2026 @ 20:59:26.073


	at com.mli.mpro.controller.TransformerController.createLead(TransformerController.java:267)


	Jan 16, 2026 @ 20:59:26.073


	at java.base/jdk.internal.reflect.DirectMethodHandleAccessor.invoke(DirectMethodHandleAccessor.java:103)


	Jan 16, 2026 @ 20:59:26.073


	at java.base/java.lang.reflect.Method.invoke(Method.java:580)


	Jan 16, 2026 @ 20:59:26.073


	at org.springframework.web.method.support.InvocableHandlerMethod.doInvoke(InvocableHandlerMethod.java:258)


	Jan 16, 2026 @ 20:59:26.073


	at org.springframework.web.method.support.InvocableHandlerMethod.invokeForRequest(InvocableHandlerMethod.java:191)


	Jan 16, 2026 @ 20:59:26.073


	at org.springframework.web.servlet.mvc.method.annotation.ServletInvocableHandlerMethod.invokeAndHandle(ServletInvocableHandlerMethod.java:118)


	Jan 16, 2026 @ 20:59:26.073


	at org.springframework.web.servlet.mvc.method.annotation.RequestMappingHandlerAdapter.invokeHandlerMethod(RequestMappingHandlerAdapter.java:991)


	Jan 16, 2026 @ 20:59:26.073


	at org.springframework.web.servlet.mvc.method.annotation.RequestMappingHandlerAdapter.handleInternal(RequestMappingHandlerAdapter.java:896)


	Jan 16, 2026 @ 20:59:26.073


	at org.springframework.web.servlet.mvc.method.AbstractHandlerMethodAdapter.handle(AbstractHandlerMethodAdapter.java:87)


	Jan 16, 2026 @ 20:59:26.073


	at org.springframework.web.servlet.DispatcherServlet.doDispatch(DispatcherServlet.java:1089)


	Jan 16, 2026 @ 20:59:26.073


	at org.springframework.web.servlet.DispatcherServlet.doService(DispatcherServlet.java:979)


	Jan 16, 2026 @ 20:59:26.073


	at org.springframework.web.servlet.FrameworkServlet.processRequest(FrameworkServlet.java:1014)
