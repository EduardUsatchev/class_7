properties([parameters([string(defaultValue: 'sda', name: 'DISK_NAME'), string('MACHINE_NAME'), string('TARGET_GB')])])
node("class5"){
    stage("clone"){
        git branch: 'main', url: 'https://github.com/EduardUsatchev/class_7.git'    
        
    }
    stage("execute"){
        sh "ls -l"
        sh "/Users/e0u00jg/anaconda3/bin/python3 disk_resizer.py"
    }
}
