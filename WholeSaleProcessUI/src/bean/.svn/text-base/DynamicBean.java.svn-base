package bean;

import oracle.adf.controller.TaskFlowId;

public class DynamicBean {
    private String taskFlowId = "/WEB-INF/WelcomeTF.xml#WelcomeTF";

    public DynamicBean() {
        super();
    }

    public TaskFlowId getDynamicTaskFlowId() {
        return TaskFlowId.parse(taskFlowId);
    }

  public String accountMappingTF()
  {
    taskFlowId = "/WEB-INF/AccountMappingTF.xml#AccountMappingTF";
    return null;
  }

    public String itemTypeAcctTF() {
        taskFlowId = "/WEB-INF/ItemTypeAcctTF.xml#ItemTypeAcctTF";
        return null;
    }
}
