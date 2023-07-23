# SIEM

## Splunk Analysis

![SIEM 1](https://github.com/beaston15/SIEM/assets/121417326/642f2f65-0567-4c6a-9e38-2fa2dd94f83e)


<p>
Looking at the Splunk dashboard we can that we have alerts from Suricata and Fortigate imported.
</p>
<br />

![explorer_BeAuIlNtpc](https://github.com/beaston15/SIEM/assets/121417326/0a94b568-e33c-4e0f-b0bd-3a6e44672368)


<p>
We can use the edit button to view the full search string that accounts for all of the alerts by Suricata. 
</p>
<br />

![SIEM 3](https://github.com/beaston15/SIEM/assets/121417326/0524d6fe-4bf8-4484-826c-1140afb63bde)


<p>
Next we will click on the "Information Leak" alert by Suricata which will then display 2 events, one of them being shown above. This will give us important information including destination ip and port, source ip and port, and lastly network protocol.
</p>
<br />

![SIEM 5](https://github.com/beaston15/SIEM/assets/121417326/67eff9ef-80b6-4989-ac4b-908801280201)


<p>
Clicking on the event gives us more details including the action of Suricata, the category of the alert, the alert signature which is highlighted and its i.d.
</p>
<br />

![SIEM 4](https://github.com/beaston15/SIEM/assets/121417326/05b64de1-4041-4b05-8f8b-547f14def0ab)


<p>
Looking at the raw text of the events we can see the same details as before about the event, such as action, signature, and as underlined the hostname and URL of the website from the website that produced the alert. 
</p>
<br />

![SIEM 6](https://github.com/beaston15/SIEM/assets/121417326/0a1614d1-abb3-4219-a55e-0db4fbc38973)


<p>
Lastly, we can click on the action under the events and see that Suricata allowed both of these events.
</p>
<br />
