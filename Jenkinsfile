node("edi"){
    stage("clone"){
        git branch: 'main', url: 'https://github.com/EduardUsatchev/class_7.git'    
        
    }
    stage("execute"){
        sh "ls -l"
        sh "/Users/e0u00jg/anaconda3/bin/python3 disk_resizer.py"
    }
}
