Follow these commands for backingup a aks cluster resource using #velero.

# Backup
`./velero backup create <backupname>`

`./velero get backup`

`./velero backup describe  <backupname>`

`./velero backup logs <backupname>`

# Restore

`./velero restore create <backupname> --from-backup <backupname>`

`./velero restore describe <backupname>`

`./velero restore logs <backupname>`


# Notes : 
 * Velero server must be insatll in the AKS cluster which has to be backup

 * Use this wiki page for any further reference.
[Velero](https://github.com/enercent/true_power_configurations/wiki/Installation-,-Backup-and-Restore-using-Velero)
