# salesforcceorg-api-integration
get fieldset type
String fieldTypeName = Schema.getGlobalDescribe().get(sobjectname).getDescribe().fields.getMap().get(fieldApiName).getDescribe().getType().name().toupperCase(); 
System.debug('*** fieldTypeName = ' + fieldTypeName);       
