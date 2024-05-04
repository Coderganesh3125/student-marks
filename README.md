# student-marksimport numpy as np
np.random.seed(42)
marks=np.random.randint(0,1001,size=60)
print('student marks; ',marks)

mean=np.mean(marks)
print('mean: ',mean)
median=np.median(marks)
print('median: ',median)
std=np.std(marks)
print('std: ',std)
max=np.max(marks)
print('max: ',max)
min=np.min(marks)
print('min: ',min)


print('desreptive statistics')
print('mean is: ',mean)
print('median is: ',median)
print('std is: ',std)
print('max is: ',max)
print('min is: ',min)

passed_student=np.sum(marks>=50)
print('passed student: ',passed_student)

pass_percentage=np.sum(marks>=50)/len(marks)*100
print('pass percentage: ',pass_percentage)

failed_student=np.sum(marks<50)
print('failed student: ',failed_student)

fail_percentage=np.sum(marks<50)/len(marks)*100
print('fail percentage: ',fail_percentage)
